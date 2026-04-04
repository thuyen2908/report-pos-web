# Instructions

- Following Playwright test failed.
- Explain why, be concise, respect Playwright best practices.
- Provide a snippet of code with the fix, if possible.

# Test info

- Name: create-tickets.feature.spec.js >> Create tickets >> Update redeem after paying with Loyalty points
- Location: dist/bdd/create-tickets.feature.spec.js:72:3

# Error details

```
Error: expect(locator).toHaveAttribute(expected) failed

Locator: locator('.MuiDataGrid-row').first().locator('.MuiDataGrid-cell[data-field="type"]')
Expected pattern: /Issuance/
Received string:  "Redemption"
Timeout: 30000ms

Call log:
  - Expect "toHaveAttribute" with timeout 30000ms
  - waiting for locator('.MuiDataGrid-row').first().locator('.MuiDataGrid-cell[data-field="type"]')
    34 × locator resolved to <div tabindex="-1" role="gridcell" aria-colspan="1" data-field="type" data-colindex="4" aria-colindex="5" title="Redemption" class="MuiDataGrid-cell MuiDataGrid-cell--textLeft">Redemption</div>
       - unexpected value "Redemption"

```

# Page snapshot

```yaml
- generic [active] [ref=e1]:
  - generic [ref=e4]:
    - banner [ref=e5]:
      - generic [ref=e6]:
        - img [ref=e9] [cursor=pointer]
        - list [ref=e12]:
          - listitem [ref=e13] [cursor=pointer]:
            - img [ref=e15]
            - generic [ref=e19]: Timesheet
          - listitem [ref=e20] [cursor=pointer]:
            - img [ref=e22]
            - generic [ref=e25]: Check In
          - listitem [ref=e26] [cursor=pointer]:
            - img [ref=e28]
            - generic [ref=e30]: Tickets
          - listitem [ref=e31] [cursor=pointer]:
            - img [ref=e33]
            - generic [ref=e40]: Turn
          - listitem [ref=e41] [cursor=pointer]:
            - img [ref=e43]
            - generic [ref=e46]: Appointment
          - listitem [ref=e47] [cursor=pointer]:
            - img [ref=e49]
            - generic [ref=e51]: Quick Sale
          - listitem [ref=e52] [cursor=pointer]:
            - img [ref=e54]
            - generic [ref=e62]: Balance
        - generic [ref=e63]:
          - generic [ref=e65] [cursor=pointer]:
            - paragraph [ref=e66]: 07:08 AM
            - generic [ref=e70]:
              - paragraph [ref=e71]: Apr
              - paragraph [ref=e72]: "04"
          - generic [ref=e75] [cursor=pointer]:
            - list [ref=e76]:
              - listitem [ref=e77]:
                - generic [ref=e78]: BLUE SALON
              - listitem [ref=e79]:
                - generic [ref=e80]: 1032 YONKERS AVE
                - paragraph [ref=e82]: Yonkers, NY, 10704 | (707) 707-1122
                - generic [ref=e83]: "Pos Blue | Station: 1"
            - img [ref=e85]
    - generic [ref=e88]:
      - generic [ref=e89]:
        - list
      - paragraph [ref=e91]: © 2026 XSoftware - 2025.12
    - main [ref=e92]:
      - generic [ref=e93]:
        - generic [ref=e94]:
          - generic [ref=e96]: "Customer: Bonnie"
          - generic [ref=e101]:
            - generic "Search" [ref=e103]:
              - generic [ref=e104]:
                - img [ref=e105]
                - searchbox "Search…" [ref=e107]
            - grid [ref=e108]:
              - generic [ref=e109]:
                - 'row "Ticket # Date Time Points Type Reason" [ref=e110]':
                  - 'columnheader "Ticket #" [ref=e111] [cursor=pointer]':
                    - generic [ref=e113]: "Ticket #"
                  - columnheader "Date" [ref=e114] [cursor=pointer]:
                    - generic [ref=e116]: Date
                  - columnheader "Time" [ref=e117] [cursor=pointer]:
                    - generic [ref=e119]: Time
                  - columnheader "Points" [ref=e120] [cursor=pointer]:
                    - generic [ref=e122]: Points
                  - columnheader "Type" [ref=e123] [cursor=pointer]:
                    - generic [ref=e125]: Type
                  - columnheader "Reason" [ref=e126] [cursor=pointer]:
                    - generic [ref=e128]: Reason
                - rowgroup [ref=e129]:
                  - row "226 04/04/2026 07:07 AM (600) Redemption" [ref=e130]:
                    - gridcell "226" [ref=e131]
                    - gridcell "04/04/2026" [ref=e132]
                    - gridcell "07:07 AM" [ref=e133]
                    - gridcell "(600)" [ref=e134]
                    - gridcell "Redemption" [ref=e135]
                    - gridcell [ref=e136]
                  - row "124 04/04/2026 05:40 AM 0 Issuance" [ref=e137]:
                    - gridcell "124" [ref=e138]
                    - gridcell "04/04/2026" [ref=e139]
                    - gridcell "05:40 AM" [ref=e140]
                    - gridcell "0" [ref=e141]
                    - gridcell "Issuance" [ref=e142]
                    - gridcell [ref=e143]
                  - row "124 04/04/2026 05:40 AM (600) Redemption" [ref=e144]:
                    - gridcell "124" [ref=e145]
                    - gridcell "04/04/2026" [ref=e146]
                    - gridcell "05:40 AM" [ref=e147]
                    - gridcell "(600)" [ref=e148]
                    - gridcell "Redemption" [ref=e149]
                    - gridcell [ref=e150]
                  - row "128 03/23/2026 05:14 AM 0 Issuance" [ref=e151]:
                    - gridcell "128" [ref=e152]
                    - gridcell "03/23/2026" [ref=e153]
                    - gridcell "05:14 AM" [ref=e154]
                    - gridcell "0" [ref=e155]
                    - gridcell "Issuance" [ref=e156]
                    - gridcell [ref=e157]
                  - row "128 03/23/2026 05:14 AM (600) Redemption" [ref=e158]:
                    - gridcell "128" [ref=e159]
                    - gridcell "03/23/2026" [ref=e160]
                    - gridcell "05:14 AM" [ref=e161]
                    - gridcell "(600)" [ref=e162]
                    - gridcell "Redemption" [ref=e163]
                    - gridcell [ref=e164]
                  - row "124 03/22/2026 09:13 PM 0 Issuance" [ref=e165]:
                    - gridcell "124" [ref=e166]
                    - gridcell "03/22/2026" [ref=e167]
                    - gridcell "09:13 PM" [ref=e168]
                    - gridcell "0" [ref=e169]
                    - gridcell "Issuance" [ref=e170]
                    - gridcell [ref=e171]
                  - row "124 03/22/2026 09:13 PM (600) Redemption" [ref=e172]:
                    - gridcell "124" [ref=e173]
                    - gridcell "03/22/2026" [ref=e174]
                    - gridcell "09:13 PM" [ref=e175]
                    - gridcell "(600)" [ref=e176]
                    - gridcell "Redemption" [ref=e177]
                    - gridcell [ref=e178]
                  - row "127 03/20/2026 05:15 AM 0 Issuance" [ref=e179]:
                    - gridcell "127" [ref=e180]
                    - gridcell "03/20/2026" [ref=e181]
                    - gridcell "05:15 AM" [ref=e182]
                    - gridcell "0" [ref=e183]
                    - gridcell "Issuance" [ref=e184]
                    - gridcell [ref=e185]
                  - row "127 03/20/2026 05:15 AM (600) Redemption" [ref=e186]:
                    - gridcell "127" [ref=e187]
                    - gridcell "03/20/2026" [ref=e188]
                    - gridcell "05:15 AM" [ref=e189]
                    - gridcell "(600)" [ref=e190]
                    - gridcell "Redemption" [ref=e191]
                    - gridcell [ref=e192]
                  - row "216 03/19/2026 09:15 PM 0 Issuance" [ref=e193]:
                    - gridcell "216" [ref=e194]
                    - gridcell "03/19/2026" [ref=e195]
                    - gridcell "09:15 PM" [ref=e196]
                    - gridcell "0" [ref=e197]
                    - gridcell "Issuance" [ref=e198]
                    - gridcell [ref=e199]
                  - row "216 03/19/2026 09:15 PM (600) Redemption" [ref=e200]:
                    - gridcell "216" [ref=e201]
                    - gridcell "03/19/2026" [ref=e202]
                    - gridcell "09:15 PM" [ref=e203]
                    - gridcell "(600)" [ref=e204]
                    - gridcell "Redemption" [ref=e205]
                    - gridcell [ref=e206]
        - generic [ref=e211]:
          - generic [ref=e212]:
            - generic [ref=e213]: ACTIVITY SUMMARY
            - generic [ref=e214]:
              - generic [ref=e215]:
                - term [ref=e216]: First Visit
                - definition [ref=e217]: 01/28/2026
              - generic [ref=e218]:
                - term [ref=e219]: Last Visit
                - definition [ref=e220]: 04/04/2026
              - generic [ref=e221]:
                - term [ref=e222]: VALUE
                - definition [ref=e223]: $9,565.00
              - generic [ref=e224]:
                - term [ref=e225]: Last Used Points
                - definition [ref=e226]: (600) pts
              - generic [ref=e227]:
                - term [ref=e228]: BALANCE
                - definition [ref=e229]: 956500 pts
          - generic [ref=e230]:
            - generic [ref=e231]: CURRENTLY VIEWING
            - generic [ref=e232]:
              - generic [ref=e234]:
                - generic [ref=e235]: "Loyalty Phone Number:"
                - generic [ref=e236]: (555) 555-5555
              - button "SEARCH ANOTHER" [ref=e238] [cursor=pointer]
        - generic [ref=e239]:
          - generic [ref=e240]: ADJUST
          - generic [ref=e241]:
            - generic [ref=e243]: "0"
            - generic [ref=e246]:
              - textbox "Enter Reason ..." [ref=e247]
              - group
            - generic [ref=e249]:
              - generic [ref=e250]:
                - button "1" [ref=e251]:
                  - generic [ref=e252]: "1"
                - button "2" [ref=e253]:
                  - generic [ref=e254]: "2"
                - button "3" [ref=e255]:
                  - generic [ref=e256]: "3"
              - generic [ref=e257]:
                - button "4" [ref=e258]:
                  - generic [ref=e259]: "4"
                - button "5" [ref=e260]:
                  - generic [ref=e261]: "5"
                - button "6" [ref=e262]:
                  - generic [ref=e263]: "6"
              - generic [ref=e264]:
                - button "7" [ref=e265]:
                  - generic [ref=e266]: "7"
                - button "8" [ref=e267]:
                  - generic [ref=e268]: "8"
                - button "9" [ref=e269]:
                  - generic [ref=e270]: "9"
              - generic [ref=e271]:
                - button [ref=e272]
                - button "0" [ref=e273]:
                  - generic [ref=e274]: "0"
                - button [ref=e275]:
                  - img [ref=e276]
            - generic [ref=e278]:
              - button "DECREASE" [disabled]
              - button "INCREASE" [disabled]
  - alert [ref=e279]
```

# Test source

```ts
  689 | 	'I should see the payment history {string} visible',
  690 | 	async ({ page }, paymentHistory: string) => {
  691 | 		const paymentHistoryElement = page
  692 | 			.locator('.xPayment__history--nameType')
  693 | 			.getByText(paymentHistory);
  694 | 		await expect(paymentHistoryElement).toHaveText(paymentHistory);
  695 | 	},
  696 | );
  697 | 
  698 | Then(
  699 | 	'I should see the payment history amount {string} visible',
  700 | 	async ({ page }, amount: string) => {
  701 | 		const paymentHistoryElement = page
  702 | 			.locator('.xPayment__history--price')
  703 | 			.getByText(amount);
  704 | 		await expect(paymentHistoryElement).toHaveText(amount);
  705 | 	},
  706 | );
  707 | 
  708 | Then(
  709 | 	'I should see the number {string} visible',
  710 | 	async ({ page }, number: string) => {
  711 | 		const numberElement = page
  712 | 			.locator('.BalanceLayout__content--number')
  713 | 			.getByText(number, { exact: true });
  714 | 
  715 | 		await expect(numberElement).toBeVisible();
  716 | 	},
  717 | );
  718 | 
  719 | Then(
  720 | 	'I should see the payment price {string}',
  721 | 	async ({ page }, price: string) => {
  722 | 		const priceElement = page
  723 | 			.locator('.xPayment__history--price')
  724 | 			.getByText(price);
  725 | 		await expect(priceElement).toHaveText(price);
  726 | 	},
  727 | );
  728 | 
  729 | When(
  730 | 	'I click on the total price of {string}',
  731 | 	async ({ page }, service: string) => {
  732 | 		const serviceContainer = page
  733 | 			.locator('.xTicketItems__info')
  734 | 			.filter({ has: page.locator('.itemName', { hasText: service }) });
  735 | 
  736 | 		await serviceContainer.locator('.xTicketItems__total').click();
  737 | 	},
  738 | );
  739 | 
  740 | When('I change the price to {string}', async ({ page }, price: string) => {
  741 | 	await page.locator('input#itemNumbers\\.amount').clear();
  742 | 	await page.locator('input#itemNumbers\\.amount').fill(price);
  743 | });
  744 | 
  745 | When(
  746 | 	'I change the quantity to {string}',
  747 | 	async ({ page }, quantity: string) => {
  748 | 		await page.locator('input#itemNumbers\\.qty').clear();
  749 | 		await page.locator('input#itemNumbers\\.qty').fill(quantity);
  750 | 	},
  751 | );
  752 | 
  753 | When('I enter a note {string}', async ({ page }, note: string) => {
  754 | 	await page.locator("[placeholder='Enter your note']").fill(note);
  755 | 	await page.getByRole('button', { name: 'Save' }).click();
  756 | });
  757 | 
  758 | Then(
  759 | 	'I should see the total price {string} visible',
  760 | 	async ({ page }, price: string) => {
  761 | 		const priceElement = page.locator('.xTicketItems__total .price', {
  762 | 			hasText: price,
  763 | 		});
  764 | 		await expect(priceElement).toBeVisible();
  765 | 	},
  766 | );
  767 | 
  768 | Then(
  769 | 	'I should see the first type {string} in the gift card detail list',
  770 | 	async ({ page }, type: string) => {
  771 | 		const firstTypeCell = page
  772 | 			.locator('.MuiDataGrid-row')
  773 | 			.first()
  774 | 			.locator('.MuiDataGrid-cell[data-field="giftCardLogType"]');
  775 | 
  776 | 		await expect(firstTypeCell).toHaveAttribute('title', new RegExp(type));
  777 | 		await expect(firstTypeCell).toContainText(type);
  778 | 	},
  779 | );
  780 | 
  781 | Then(
  782 | 	'I should see the first type {string} in the loyalty detail list',
  783 | 	async ({ page }, type: string) => {
  784 | 		const firstTypeCell = page
  785 | 			.locator('.MuiDataGrid-row')
  786 | 			.first()
  787 | 			.locator('.MuiDataGrid-cell[data-field="type"]');
  788 | 
> 789 | 		await expect(firstTypeCell).toHaveAttribute('title', new RegExp(type));
      |                               ^ Error: expect(locator).toHaveAttribute(expected) failed
  790 | 		await expect(firstTypeCell).toContainText(type);
  791 | 	},
  792 | );
  793 | 
  794 | Then(
  795 | 	'I should see the first amount {string} in the gift card detail list',
  796 | 	async ({ page }, amount: string) => {
  797 | 		const firstAmountCell = page
  798 | 			.locator('.MuiDataGrid-row')
  799 | 			.first()
  800 | 			.locator('.MuiDataGrid-cell[data-field="amount"]');
  801 | 
  802 | 		await expect(firstAmountCell).toContainText(amount);
  803 | 	},
  804 | );
  805 | 
  806 | Then(
  807 | 	'I should see the first date is today in the gift card detail list',
  808 | 	async ({ page }) => {
  809 | 		const firstDateCell = page
  810 | 			.locator('.MuiDataGrid-row')
  811 | 			.first()
  812 | 			.locator('.MuiDataGrid-cell[data-field="createdAt"]');
  813 | 		const formattedToday = await page.evaluate(() => {
  814 | 			const today = new Date();
  815 | 			return today.toLocaleDateString('en-US', {
  816 | 				year: 'numeric',
  817 | 				month: '2-digit',
  818 | 				day: '2-digit',
  819 | 			});
  820 | 		});
  821 | 		await expect(firstDateCell).toContainText(formattedToday);
  822 | 	},
  823 | );
  824 | 
  825 | Then(
  826 | 	'I should see the first date is not today in the gift card detail list',
  827 | 	async ({ page }) => {
  828 | 		const firstDateCell = page
  829 | 			.locator('.MuiDataGrid-row')
  830 | 			.first()
  831 | 			.locator('.MuiDataGrid-cell[data-field="createdAt"]');
  832 | 		const formattedToday = await page.evaluate(() => {
  833 | 			const today = new Date();
  834 | 			return today.toLocaleDateString('en-US', {
  835 | 				year: 'numeric',
  836 | 				month: '2-digit',
  837 | 				day: '2-digit',
  838 | 			});
  839 | 		});
  840 | 		await expect(firstDateCell).not.toContainText(formattedToday);
  841 | 	},
  842 | );
  843 | 
  844 | Then(
  845 | 	'I should see the first date is today in the loyalty detail list',
  846 | 	async ({ page }) => {
  847 | 		const firstDateCell = page
  848 | 			.locator('.MuiDataGrid-row')
  849 | 			.first()
  850 | 			.locator('.MuiDataGrid-cell[data-field="createdDate"]');
  851 | 		const formattedToday = await page.evaluate(() => {
  852 | 			const today = new Date();
  853 | 			return today.toLocaleDateString('en-US', {
  854 | 				year: 'numeric',
  855 | 				month: '2-digit',
  856 | 				day: '2-digit',
  857 | 			});
  858 | 		});
  859 | 		await expect(firstDateCell).toContainText(formattedToday);
  860 | 	},
  861 | );
  862 | 
  863 | Then(
  864 | 	'I should see the note {string} visible',
  865 | 	async ({ page }, note: string) =>
  866 | 		await expect(page.locator('.xTicketItems__note')).toContainText(note),
  867 | );
  868 | 
  869 | Then(
  870 | 	'I should see the loyalty phone {string} visible',
  871 | 	async ({ page }, phone: string) => {
  872 | 		const loyaltyPhoneElement = page
  873 | 			.locator('.Bloyalty__phone')
  874 | 			.getByText(phone, { exact: true });
  875 | 
  876 | 		await expect(loyaltyPhoneElement).toBeVisible();
  877 | 	},
  878 | );
  879 | 
  880 | Then(
  881 | 	'I should see the first type {string} in the loyal detail list',
  882 | 	async ({ page }, type: string) => {
  883 | 		const firstTypeCell = page
  884 | 			.locator('.MuiDataGrid-row')
  885 | 			.first()
  886 | 			.locator('.MuiDataGrid-cell[data-field="type"]');
  887 | 
  888 | 		await expect(firstTypeCell).toHaveAttribute('title', type);
  889 | 	},
```