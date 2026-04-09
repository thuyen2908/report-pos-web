# Instructions

- Following Playwright test failed.
- Explain why, be concise, respect Playwright best practices.
- Provide a snippet of code with the fix, if possible.

# Test info

- Name: payroll.feature.spec.js >> Payroll >> Show payroll formula
- Location: dist/bdd/payroll.feature.spec.js:337:3

# Error details

```
Error: expect(locator).toBeVisible() failed

Locator: locator('.MuiDataGrid-main').getByText('Addison', { exact: true })
Expected: visible
Timeout: 30000ms
Error: element(s) not found

Call log:
  - Expect "toBeVisible" with timeout 30000ms
  - waiting for locator('.MuiDataGrid-main').getByText('Addison', { exact: true })

```

# Page snapshot

```yaml
- generic [ref=e1]:
  - generic [ref=e4]:
    - banner [ref=e5]:
      - generic [ref=e6]:
        - img [ref=e9] [cursor=pointer]
        - generic [ref=e11]:
          - paragraph [ref=e12]: Payroll
          - paragraph
        - generic [ref=e13]:
          - generic [ref=e15] [cursor=pointer]:
            - paragraph [ref=e16]: 04:13 AM
            - generic [ref=e20]:
              - paragraph [ref=e21]: Apr
              - paragraph [ref=e22]: "09"
          - generic [ref=e25] [cursor=pointer]:
            - list [ref=e26]:
              - listitem [ref=e27]:
                - generic [ref=e28]: BLUE SALON
              - listitem [ref=e29]:
                - generic [ref=e30]: 1032 YONKERS AVE
                - paragraph [ref=e32]: Yonkers, NY, 10704 | (707) 707-1122
                - generic [ref=e33]: "Pos Blue | Station: 1"
            - img [ref=e35]
    - generic [ref=e38]:
      - generic [ref=e39]:
        - list
      - paragraph [ref=e41]: © 2026 XSoftware - 2025.12
    - main [ref=e42]:
      - generic [ref=e43]:
        - generic [ref=e45]:
          - generic [ref=e46]:
            - button "04/09/2026" [ref=e47] [cursor=pointer]
            - button "04/09/2026" [ref=e48] [cursor=pointer]
            - generic [ref=e49]:
              - button [ref=e50] [cursor=pointer]:
                - img [ref=e51]
              - button [ref=e53] [cursor=pointer]:
                - img [ref=e55]
          - generic [ref=e57]:
            - generic [ref=e58]: Type
            - generic [ref=e59]:
              - combobox [ref=e60] [cursor=pointer]:
                - generic [ref=e62]: Owner View
              - textbox: owner
              - img
              - group:
                - generic: Type
          - generic [ref=e67]:
            - generic "Search" [ref=e69]:
              - generic [ref=e70]:
                - img [ref=e71]
                - searchbox "Search…" [active] [ref=e73]: Addison
                - button "Clear" [ref=e74] [cursor=pointer]:
                  - img [ref=e75]
            - grid [ref=e77]:
              - generic [ref=e78]:
                - row "Name" [ref=e79]:
                  - columnheader [ref=e80]
                  - columnheader "Name" [ref=e81] [cursor=pointer]:
                    - generic [ref=e83]: Name
                - generic [ref=e85]: No rows
                - rowgroup
        - generic [ref=e87]:
          - generic [ref=e88]:
            - generic [ref=e89]:
              - tablist [ref=e92]:
                - tab "SINGLE PAYROLL" [selected] [ref=e93] [cursor=pointer]
                - tab "SUMMARY PAYROLL" [ref=e94] [cursor=pointer]
                - tab "PAYROLL DETAILS" [ref=e95] [cursor=pointer]
                - tab "TIMESHEET" [ref=e96] [cursor=pointer]
                - tab "PAYSUB" [ref=e97] [cursor=pointer]
                - tab "DOCUMENTS" [ref=e98] [cursor=pointer]
              - img [ref=e100] [cursor=pointer]
            - generic [ref=e102]:
              - button "Recalculation" [disabled]:
                - generic:
                  - img
                - text: Recalculation
              - button "Save" [disabled]:
                - generic:
                  - img
                - text: Save
              - button "Print" [ref=e103] [cursor=pointer]:
                - img [ref=e105]
                - text: Print
          - tabpanel "SINGLE PAYROLL" [ref=e109]
  - alert [ref=e117]
```

# Test source

```ts
  1448 | );
  1449 | 
  1450 | Then(
  1451 | 	'I should see the package item {string} in my cart',
  1452 | 	async ({ page }, service: string) => {
  1453 | 		const servicePackageItem = page
  1454 | 			.locator('.ServicePackageItem .xTicketItems__name')
  1455 | 			.getByText(service);
  1456 | 		await expect(servicePackageItem).toBeVisible();
  1457 | 		await expect(servicePackageItem).toHaveText(service);
  1458 | 	},
  1459 | );
  1460 | 
  1461 | Then('I should see the detail {string}', async ({ page }, detail: string) => {
  1462 | 	const itemDetail = page.locator('.xTicketItems__detail').getByText(detail);
  1463 | 
  1464 | 	await expect(itemDetail).toContainText(detail);
  1465 | });
  1466 | 
  1467 | Then(
  1468 | 	'I should see multiple {string} details',
  1469 | 	async ({ page }, detail: string) => {
  1470 | 		const itemDetails = await page
  1471 | 			.locator('.xTicketItems__detail')
  1472 | 			.getByText(detail)
  1473 | 			.all();
  1474 | 
  1475 | 		expect(itemDetails.length).toBeGreaterThan(1);
  1476 | 	},
  1477 | );
  1478 | 
  1479 | Then(
  1480 | 	'I should see a popup dialog containing the title {string}',
  1481 | 	async ({ page }, title: string) => {
  1482 | 		const dialogTitle = page.locator('#alert-dialog-title').getByText(title);
  1483 | 		await expect(dialogTitle).toBeVisible();
  1484 | 		await expect(dialogTitle).toContainText(title);
  1485 | 	},
  1486 | );
  1487 | 
  1488 | When(
  1489 | 	'I click on the charge item {string} in the ticket adjustment screen',
  1490 | 	async ({ page }, button: string) => {
  1491 | 		const buttonItem = page
  1492 | 			.locator('.xFixTicket__main--chargeItem')
  1493 | 			.getByText(button);
  1494 | 		await buttonItem.click();
  1495 | 	},
  1496 | );
  1497 | 
  1498 | Then(
  1499 | 	'I should see the charge display {string}',
  1500 | 	async ({ page }, charge: string) => {
  1501 | 		const chargedItem = page
  1502 | 			.locator('.xFixTicket__main--chargeItem')
  1503 | 			.getByText(charge);
  1504 | 		await expect(chargedItem).toContainText(charge);
  1505 | 	},
  1506 | );
  1507 | 
  1508 | When(
  1509 | 	'I select the service {string} in my cart',
  1510 | 	async ({ page }, service: string) => {
  1511 | 		const serviceElement = page
  1512 | 			.locator('.xTicketItems__content')
  1513 | 			.getByText(service, { exact: true });
  1514 | 		await serviceElement.click();
  1515 | 	},
  1516 | );
  1517 | 
  1518 | Then('I should see the check icon', async ({ page }) => {
  1519 | 	const checkIcon = page.locator('[data-testid="XCheckIcon"]');
  1520 | 	await expect(checkIcon).toBeVisible();
  1521 | });
  1522 | 
  1523 | When(
  1524 | 	'I click on the action {string} button',
  1525 | 	async ({ page }, button: string) => {
  1526 | 		const buttonItem = page
  1527 | 			.locator('.xFixTicket__action--btn')
  1528 | 			.getByText(button);
  1529 | 		await buttonItem.click();
  1530 | 	},
  1531 | );
  1532 | 
  1533 | When(
  1534 | 	'I select the employee {string} in the ticket adjustment screen',
  1535 | 	async ({ page }, employee: string) => {
  1536 | 		const employeeElement = page
  1537 | 			.locator('.ListItemEmployee__wrap')
  1538 | 			.getByText(employee, { exact: true });
  1539 | 		await expect(employeeElement).toBeVisible();
  1540 | 		await employeeElement.click();
  1541 | 	},
  1542 | );
  1543 | 
  1544 | When('I select the employee {string}', async ({ page }, employee: string) => {
  1545 | 	const employeeElement = page
  1546 | 		.locator('.MuiDataGrid-main')
  1547 | 		.getByText(employee, { exact: true });
> 1548 | 	await expect(employeeElement).toBeVisible();
       |                                ^ Error: expect(locator).toBeVisible() failed
  1549 | 	await employeeElement.click();
  1550 | });
  1551 | 
  1552 | Then(
  1553 | 	'I verify all single payroll details for Owner View are displayed correctly',
  1554 | 	async ({ page }) => {
  1555 | 		const fields = [
  1556 | 			'Payroll Date:',
  1557 | 			'Technician Name:',
  1558 | 			'Payroll Type:',
  1559 | 			'# of Work Days:',
  1560 | 			'Sale Summary',
  1561 | 			'Total:',
  1562 | 			'Product:',
  1563 | 			'Service:',
  1564 | 			'Service Deductions',
  1565 | 			'Item Discount:',
  1566 | 			'Ticket Discount:',
  1567 | 			'Item Supply Fee:',
  1568 | 			'Ticket Supply Fee:',
  1569 | 			'Loyalty Redemption:',
  1570 | 			'Other Deductions',
  1571 | 			'Daily Maintenance Fee:',
  1572 | 			'Credit Card Fee:',
  1573 | 			'Tax Withheld on Cash:',
  1574 | 			'Pay Calculations',
  1575 | 			'Net Total Sale:',
  1576 | 			'Product Commission:',
  1577 | 			'Service Commission:',
  1578 | 			'Net Commission:',
  1579 | 			'Net Non-Cash Tip (100.00%):',
  1580 | 			'Check (50.00%):',
  1581 | 			'Cash (50.00%):',
  1582 | 			'Pay 1:',
  1583 | 			'Pay 2:',
  1584 | 			'Total Payout:',
  1585 | 			'Gross Profit:',
  1586 | 		];
  1587 | 		const card = page.locator('.MuiCard-root.render-bill');
  1588 | 
  1589 | 		for (const label of fields) {
  1590 | 			const fieldLocator = card.getByText(label.trim(), { exact: false });
  1591 | 			await expect(fieldLocator).toBeVisible();
  1592 | 		}
  1593 | 	},
  1594 | );
  1595 | 
  1596 | Then(
  1597 | 	'I should see the categories displayed correctly in check-in',
  1598 | 	async ({ page }) => {
  1599 | 		const expectedCategories = [
  1600 | 			'MANI & PEDI',
  1601 | 			'FULL SET & FILL IN',
  1602 | 			'ADDITIONAL SERVICE',
  1603 | 		];
  1604 | 
  1605 | 		const categoryElements = page.locator('[role="tablist"] span');
  1606 | 		await expect(categoryElements).toHaveCount(expectedCategories.length);
  1607 | 
  1608 | 		for (let i = 0; i < expectedCategories.length; i++) {
  1609 | 			const categoryName = await categoryElements.nth(i).innerText();
  1610 | 			expect(categoryName.trim()).toBe(expectedCategories[i]);
  1611 | 		}
  1612 | 	},
  1613 | );
  1614 | 
  1615 | When(
  1616 | 	'I click on the {string} button in the create new customer dialog',
  1617 | 	async ({ page }, button: string) => {
  1618 | 		const buttonElement = page
  1619 | 			.locator('.customDialogAction')
  1620 | 			.getByRole('button', { name: button });
  1621 | 		await buttonElement.click();
  1622 | 	},
  1623 | );
  1624 | 
  1625 | When(
  1626 | 	'I select the booked of {string}',
  1627 | 	async ({ page }, customerName: string) => {
  1628 | 		const appointmentElement = page
  1629 | 			.locator('.e-appointment .event-cellTime')
  1630 | 			.last();
  1631 | 		await expect(appointmentElement).toBeVisible();
  1632 | 		await expect(appointmentElement).toContainText(customerName);
  1633 | 		await appointmentElement.click();
  1634 | 	},
  1635 | );
  1636 | 
  1637 | Then(
  1638 | 	'I should see the categories displayed correctly in ticket view',
  1639 | 	async ({ page }) => {
  1640 | 		const expectedCategories = [
  1641 | 			'MANI & PEDI',
  1642 | 			'FULL SET & FILL IN',
  1643 | 			'ADDITIONAL SERVICE',
  1644 | 			'GIFT CARD',
  1645 | 		];
  1646 | 
  1647 | 		const categoryElements = page.locator('[role="tablist"] span');
  1648 | 		await expect(categoryElements).toHaveCount(expectedCategories.length);
```