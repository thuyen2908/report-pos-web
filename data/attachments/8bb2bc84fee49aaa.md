# Instructions

- Following Playwright test failed.
- Explain why, be concise, respect Playwright best practices.
- Provide a snippet of code with the fix, if possible.

# Test info

- Name: close-out.feature.spec.js >> Close Out report >> Technician report display correctly
- Location: dist/bdd/close-out.feature.spec.js:15:3

# Error details

```
Error: expect(locator).toHaveText(expected) failed

Locator:  locator('.summary-row').filter({ has: locator('.summary-label').filter({ hasText: /^Gift Card Sale$/i }) }).locator('.summary-value')
Expected: "$100.00"
Received: "$200.00"
Timeout:  30000ms

Call log:
  - Expect "toHaveText" with timeout 30000ms
  - waiting for locator('.summary-row').filter({ has: locator('.summary-label').filter({ hasText: /^Gift Card Sale$/i }) }).locator('.summary-value')
    34 × locator resolved to <div class="summary-value">$200.00</div>
       - unexpected value "$200.00"

```

# Page snapshot

```yaml
- generic [ref=e1]:
  - generic [ref=e4]:
    - banner [ref=e5]:
      - generic [ref=e6]:
        - img [ref=e9] [cursor=pointer]
        - generic [ref=e11]:
          - paragraph [ref=e12]: Close Out
          - paragraph
        - generic [ref=e13]:
          - generic [ref=e15] [cursor=pointer]:
            - paragraph [ref=e16]: 12:47 AM
            - generic [ref=e20]:
              - paragraph [ref=e21]: Apr
              - paragraph [ref=e22]: "06"
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
          - generic [ref=e47]:
            - generic [ref=e48]:
              - button "Print" [ref=e49] [cursor=pointer]:
                - img [ref=e51]
                - text: Print
              - button "Cash Drawer" [ref=e54] [cursor=pointer]:
                - img [ref=e56]
                - text: Cash Drawer
            - button "Hide" [ref=e60] [cursor=pointer]
          - generic [ref=e62]:
            - button "04/06/2026" [ref=e63] [cursor=pointer]
            - button "04/06/2026" [ref=e64] [cursor=pointer]
            - button [ref=e65] [cursor=pointer]:
              - img [ref=e66]
        - generic [ref=e68]:
          - generic [ref=e72]:
            - button "Combine view" [ref=e73] [cursor=pointer]:
              - img [ref=e74]
            - generic [ref=e77]:
              - paragraph [ref=e78]: Technician Report
              - generic [ref=e79]:
                - generic [ref=e80]:
                  - generic [ref=e81]: "Date:"
                  - generic [ref=e82]: 04/06/2026
                - generic [ref=e83]:
                  - generic [ref=e84]: "Clock In:"
                  - generic [ref=e85]: 12:45 AM
                - generic [ref=e87]: "Clock Out:"
                - generic [ref=e89]:
                  - generic [ref=e90]: "Technician Name:"
                  - generic [ref=e91]: Elena
              - generic [ref=e94]: Item Sales Details
              - generic [ref=e96]:
                - generic [ref=e97]:
                  - generic [ref=e98]: Item Name
                  - generic [ref=e99]: Ticket
                  - generic [ref=e100]: QTY
                  - generic [ref=e101]: Tip
                  - generic [ref=e102]: Amount
                - generic [ref=e103]:
                  - generic [ref=e104]:
                    - generic [ref=e105]: Manicure
                    - generic [ref=e106]: Shampoo
                    - generic [ref=e107]: Gift card $100
                  - generic [ref=e108]: "116"
                  - generic [ref=e109]: "3"
                  - generic [ref=e110]: $10.00
                  - generic [ref=e111]: $221.70
                - generic [ref=e112]:
                  - generic [ref=e113]:
                    - generic [ref=e114]: Manicure
                    - generic [ref=e115]: Shampoo
                    - generic [ref=e116]: Gift card $100
                  - generic [ref=e117]: "117"
                  - generic [ref=e118]: "3"
                  - generic [ref=e119]: $10.00
                  - generic [ref=e120]: $221.70
                - generic [ref=e121]:
                  - generic [ref=e122]: Total
                  - generic [ref=e124]: "6"
                  - generic [ref=e125]: $20.00
                  - generic [ref=e126]: $443.40
              - generic [ref=e129]: Summary
              - generic [ref=e131]:
                - generic [ref=e132]:
                  - generic [ref=e133]: Gift Card Sale
                  - generic [ref=e134]: $200.00
                - generic [ref=e135]:
                  - generic [ref=e136]: Service/Product Sale
                  - generic [ref=e137]: $243.40
                - generic [ref=e138]:
                  - generic [ref=e139]: Net Total Sale
                  - generic [ref=e140]: $237.40
                - generic [ref=e141]:
                  - generic [ref=e142]: Commission
                  - generic [ref=e143]: $92.44
                - generic [ref=e144]:
                  - generic [ref=e145]: Non-Cash Tip
                  - generic [ref=e146]: $20.00
                - generic [ref=e147]:
                  - generic [ref=e148]: CASH RECEIVED
                  - generic [ref=e149]: $100.00
                - generic [ref=e150]:
                  - generic [ref=e151]: CASH IN/OUT
                  - generic [ref=e152]: $0.00
                - generic [ref=e153]:
                  - generic [ref=e154]: I OWE SALON
                  - generic [ref=e155]: $100.00
          - generic [ref=e157]:
            - generic [ref=e158]:
              - button "Sales Report" [ref=e159] [cursor=pointer]
              - button "Technician Report" [ref=e160] [cursor=pointer]
              - button "Clock Out All" [ref=e161] [cursor=pointer]
              - button "Transactions" [ref=e162] [cursor=pointer]
            - generic [ref=e164]:
              - generic "Search" [ref=e166]:
                - generic [ref=e167]:
                  - img [ref=e168]
                  - searchbox "Search…" [ref=e170]: Elena
                  - button "Clear" [ref=e171] [cursor=pointer]:
                    - img [ref=e172]
              - grid [ref=e174]:
                - generic [ref=e175]:
                  - row "Name Clock In Clock Out Action" [ref=e176]:
                    - columnheader "Name" [ref=e177] [cursor=pointer]:
                      - generic [ref=e179]: Name
                    - columnheader "Clock In" [ref=e180] [cursor=pointer]:
                      - generic [ref=e182]: Clock In
                    - columnheader "Clock Out" [ref=e183] [cursor=pointer]:
                      - generic [ref=e185]: Clock Out
                    - columnheader "Action" [ref=e186] [cursor=pointer]:
                      - generic [ref=e188]: Action
                  - rowgroup [ref=e189]:
                    - row "E Elena 04/06/2026 12:45 AM Clock Out" [selected] [ref=e190] [cursor=pointer]:
                      - gridcell "E Elena" [ref=e191]:
                        - generic [ref=e192]:
                          - generic [ref=e193]: E
                          - generic [ref=e194]: Elena
                      - gridcell "04/06/2026 12:45 AM" [active] [ref=e195]
                      - gridcell [ref=e196]
                      - gridcell "Clock Out" [ref=e197]:
                        - button "Clock Out" [ref=e198]:
                          - img [ref=e199]
                          - generic [ref=e204]: Clock Out
  - alert [ref=e208]
```

# Test source

```ts
  3904 | );
  3905 | 
  3906 | Then(
  3907 | 	'I should see the detail {string} in the bill render',
  3908 | 	async ({ page }, detail: string) => {
  3909 | 		const colonIndex = detail.indexOf(':');
  3910 | 		if (colonIndex === -1) {
  3911 | 			throw new Error(
  3912 | 				`Invalid detail format: "${detail}". Expected format: "Label: Value"`,
  3913 | 			);
  3914 | 		}
  3915 | 
  3916 | 		const labelPart = detail.substring(0, colonIndex).trim(); // E.g.: "Technician Name"
  3917 | 		const expectedValue = detail.substring(colonIndex + 1).trim(); // E.g.: "Elena"
  3918 | 
  3919 | 		const infoRow = page.locator('.info-row').filter({
  3920 | 			has: page.locator('.info-label', {
  3921 | 				hasText: new RegExp(`^\\s*${labelPart}\\s*:?\\s*$`),
  3922 | 			}),
  3923 | 		});
  3924 | 
  3925 | 		await expect(infoRow).toBeVisible();
  3926 | 
  3927 | 		const valueElement = infoRow.locator('.info-value');
  3928 | 		await expect(valueElement).toBeVisible();
  3929 | 		await expect(valueElement).toContainText(expectedValue);
  3930 | 	},
  3931 | );
  3932 | 
  3933 | Then(
  3934 | 	'I should see the {string} with value {string} in the sale row detail',
  3935 | 	async ({ page }, field: string, value: string) => {
  3936 | 		const billRender = page.locator('.bill-render');
  3937 | 		await expect(billRender).toBeVisible();
  3938 | 
  3939 | 		const salesRow = billRender
  3940 | 			.locator('.sales-details .sales-row')
  3941 | 			.filter({ hasNot: billRender.locator('.total-row') })
  3942 | 			.first();
  3943 | 		await expect(salesRow).toBeVisible();
  3944 | 
  3945 | 		const fieldToSelector: Record<string, string> = {
  3946 | 			'Item Name': '.item-name',
  3947 | 			QTY: '.quantity',
  3948 | 			Tip: '.tip',
  3949 | 			Amount: '.amount',
  3950 | 		};
  3951 | 
  3952 | 		const selector = fieldToSelector[field];
  3953 | 		if (!selector) {
  3954 | 			throw new Error(
  3955 | 				`Unsupported sale row field: "${field}". Supported fields: ${Object.keys(
  3956 | 					fieldToSelector,
  3957 | 				).join(', ')}`,
  3958 | 			);
  3959 | 		}
  3960 | 
  3961 | 		const cell = salesRow.locator(selector);
  3962 | 		await expect(cell).toBeVisible();
  3963 | 
  3964 | 		if (field === 'Item Name') {
  3965 | 			const cellText = (await cell.innerText()).replace(/\s+/g, ' ').trim();
  3966 | 			const expected = value.replace(/\s+/g, ' ').trim();
  3967 | 			expect(cellText).toContain(expected);
  3968 | 			return;
  3969 | 		}
  3970 | 
  3971 | 		await expect(cell).toHaveText(value, { useInnerText: true });
  3972 | 	},
  3973 | );
  3974 | 
  3975 | Then(
  3976 | 	'I should see the summary detail {string} in the bill render',
  3977 | 	async ({ page }, detail: string) => {
  3978 | 		const match = detail.match(/^(.*?)\s+(\$?-?[\d,.]+(?:\/\d+)?)$/);
  3979 | 
  3980 | 		let label: string;
  3981 | 		let expectedValue: string;
  3982 | 
  3983 | 		if (match) {
  3984 | 			label = match[1].trim();
  3985 | 			expectedValue = match[2].trim();
  3986 | 		} else {
  3987 | 			const lastSpaceIndex = detail.trim().lastIndexOf(' ');
  3988 | 			label = detail.trim().slice(0, lastSpaceIndex).trim();
  3989 | 			expectedValue = detail
  3990 | 				.trim()
  3991 | 				.slice(lastSpaceIndex + 1)
  3992 | 				.trim();
  3993 | 		}
  3994 | 
  3995 | 		const summaryRow = page.locator('.summary-row').filter({
  3996 | 			has: page.locator('.summary-label', {
  3997 | 				hasText: new RegExp(`^${label}$`, 'i'),
  3998 | 			}),
  3999 | 		});
  4000 | 
  4001 | 		await expect(summaryRow).toBeVisible();
  4002 | 
  4003 | 		const valueElement = summaryRow.locator('.summary-value');
> 4004 | 		await expect(valueElement).toHaveText(expectedValue);
       |                              ^ Error: expect(locator).toHaveText(expected) failed
  4005 | 	},
  4006 | );
  4007 | 
  4008 | Then(
  4009 | 	'I should see the Tech, Deductions, Tip, Amount as {string} in the bill render',
  4010 | 	async ({ page }, expectedRow: string) => {
  4011 | 		const [tech, deductions, tip, amount] = expectedRow.split(' ');
  4012 | 
  4013 | 		const row = page.locator('.sales-row').filter({
  4014 | 			has: page.locator('.tech-name', { hasText: tech }),
  4015 | 		});
  4016 | 
  4017 | 		await expect(row).toBeVisible();
  4018 | 
  4019 | 		await expect(row.locator('.deductions')).toHaveText(deductions);
  4020 | 		await expect(row.locator('.tip')).toHaveText(tip);
  4021 | 		await expect(row.locator('.amount')).toHaveText(amount);
  4022 | 	},
  4023 | );
  4024 | 
  4025 | When(
  4026 | 	'I search for {string} and select the result',
  4027 | 	async ({ page }, text: string) => {
  4028 | 		await page.locator('input[placeholder="Search…"]').first().fill(text);
  4029 | 		await page.waitForTimeout(5000);
  4030 | 		await page.locator('.MuiDataGrid-row').first().click();
  4031 | 	},
  4032 | );
  4033 | 
  4034 | Then(
  4035 | 	'I should see the Turn, Regular, Total, Left as {string} in turn details',
  4036 | 	async ({ page }, expectedValues: string) => {
  4037 | 		const values = expectedValues.split(' ');
  4038 | 		expect(values).toHaveLength(4);
  4039 | 
  4040 | 		const [expectedTurn, expectedRegular, expectedTotal, expectedLeft] = values;
  4041 | 		const detailsTable = page.locator('table.table-fixed');
  4042 | 		const dataRow = detailsTable.locator('tr').nth(1);
  4043 | 		await expect(dataRow).toBeVisible();
  4044 | 
  4045 | 		const turnCell = dataRow.locator('td').nth(1);
  4046 | 		const regularCell = dataRow.locator('td').nth(2);
  4047 | 		const totalCell = dataRow.locator('td').nth(3);
  4048 | 		const leftCell = dataRow.locator('td').nth(4);
  4049 | 
  4050 | 		await expect(turnCell).toHaveText(expectedTurn);
  4051 | 		await expect(regularCell).toHaveText(expectedRegular);
  4052 | 		await expect(totalCell).toHaveText(expectedTotal);
  4053 | 		await expect(leftCell).toHaveText(expectedLeft);
  4054 | 	},
  4055 | );
  4056 | 
  4057 | When(
  4058 | 	'I select the first ticket with payment {string}',
  4059 | 	async ({ page }, total: string) => {
  4060 | 		const ticketElement = page
  4061 | 			.locator('.MuiDataGrid-row')
  4062 | 			.first()
  4063 | 			.filter({
  4064 | 				has: page.locator('[data-field="paymentTotal"]', { hasText: total }),
  4065 | 			});
  4066 | 
  4067 | 		await ticketElement.click();
  4068 | 	},
  4069 | );
  4070 | 
  4071 | When(
  4072 | 	'I click on item button {string}',
  4073 | 	async ({ page }, buttonName: string) => {
  4074 | 		const itemText = page
  4075 | 			.locator('.box-bill')
  4076 | 			.getByText(buttonName, { exact: true });
  4077 | 		await expect(itemText).toBeVisible();
  4078 | 		await itemText.click();
  4079 | 	},
  4080 | );
  4081 | 
  4082 | When(
  4083 | 	'I click on the avatar of the first ticket with payment {string}',
  4084 | 	async ({ page }, amount: string) => {
  4085 | 		const paymentRow = page
  4086 | 			.locator('.MuiDataGrid-row')
  4087 | 			.filter({
  4088 | 				has: page.locator('[data-field="paymentTotal"]', { hasText: amount }),
  4089 | 			})
  4090 | 			.filter({
  4091 | 				has: page.locator('[data-field="paymentMethod"]', { hasText: /.+/ }),
  4092 | 			})
  4093 | 			.first();
  4094 | 		await expect(paymentRow).toBeVisible();
  4095 | 
  4096 | 		const avatarCell = paymentRow.locator('[data-field="avatar"]').first();
  4097 | 		await expect(avatarCell).toBeVisible();
  4098 | 		await avatarCell.click();
  4099 | 	},
  4100 | );
  4101 | 
  4102 | Then(
  4103 | 	'I should see the Employee, Price, Tip as {string} on the work slip',
  4104 | 	async ({ page }, expectedValues: string) => {
```