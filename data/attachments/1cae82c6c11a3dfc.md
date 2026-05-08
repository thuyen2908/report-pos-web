# Instructions

- Following Playwright test failed.
- Explain why, be concise, respect Playwright best practices.
- Provide a snippet of code with the fix, if possible.

# Test info

- Name: create-tickets.feature.spec.js >> Create tickets >> Sell a Gift Card rewrite amount
- Location: dist/bdd/create-tickets.feature.spec.js:439:3

# Error details

```
Error: expect(locator).toContainText(expected) failed

Locator: locator('.MuiDataGrid-row').first().locator('.MuiDataGrid-cell[data-field="amount"]')
Expected substring: "$100.00"
Received string:    "($200.00)"
Timeout: 30000ms

Call log:
  - Expect "toContainText" with timeout 30000ms
  - waiting for locator('.MuiDataGrid-row').first().locator('.MuiDataGrid-cell[data-field="amount"]')
    34 × locator resolved to <div tabindex="-1" role="gridcell" aria-colspan="1" data-colindex="3" aria-colindex="4" title="($200.00)" data-field="amount" class="MuiDataGrid-cell MuiDataGrid-cell--textRight">($200.00)</div>
       - unexpected value "($200.00)"

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
            - paragraph [ref=e66]: 11:23 PM
            - generic [ref=e70]:
              - paragraph [ref=e71]: May
              - paragraph [ref=e72]: "07"
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
          - generic [ref=e95]: DETAILS
          - generic [ref=e100]:
            - generic "Search" [ref=e102]:
              - generic [ref=e103]:
                - img [ref=e104]
                - searchbox "Search…" [ref=e106]
            - grid [ref=e107]:
              - generic [ref=e108]:
                - 'row "Ticket # Date Time Amount Type Reason" [ref=e109]':
                  - 'columnheader "Ticket #" [ref=e110] [cursor=pointer]':
                    - generic [ref=e112]: "Ticket #"
                  - columnheader "Date" [ref=e113] [cursor=pointer]:
                    - generic [ref=e115]: Date
                  - columnheader "Time" [ref=e116] [cursor=pointer]:
                    - generic [ref=e118]: Time
                  - columnheader "Amount" [ref=e119] [cursor=pointer]:
                    - generic [ref=e121]: Amount
                  - columnheader "Type" [ref=e122] [cursor=pointer]:
                    - generic [ref=e124]: Type
                  - columnheader "Reason" [ref=e125] [cursor=pointer]:
                    - generic [ref=e127]: Reason
                - rowgroup [ref=e128]:
                  - row "140 05/07/2026 11:23 PM ($200.00) OverwriteAdjust" [ref=e129]:
                    - gridcell "140" [ref=e130]
                    - gridcell "05/07/2026" [ref=e131]
                    - gridcell "11:23 PM" [ref=e132]
                    - gridcell "($200.00)" [ref=e133]
                    - gridcell "OverwriteAdjust" [ref=e134]
                    - gridcell [ref=e135]
                  - row "140 05/07/2026 11:23 PM $100.00 ActivateOverwrite" [ref=e138]:
                    - gridcell "140" [ref=e139]
                    - gridcell "05/07/2026" [ref=e140]
                    - gridcell "11:23 PM" [ref=e141]
                    - gridcell "$100.00" [ref=e142]
                    - gridcell "ActivateOverwrite" [ref=e143]
                    - gridcell [ref=e144]
                  - row "178 04/09/2026 04:22 AM $100.00 ActivateAddOn" [ref=e147]:
                    - gridcell "178" [ref=e148]
                    - gridcell "04/09/2026" [ref=e149]
                    - gridcell "04:22 AM" [ref=e150]
                    - gridcell "$100.00" [ref=e151]
                    - gridcell "ActivateAddOn" [ref=e152]
                    - gridcell [ref=e153]
                  - row "150 04/09/2026 04:18 AM $100.00 ActivateOverwrite" [ref=e156]:
                    - gridcell "150" [ref=e157]
                    - gridcell "04/09/2026" [ref=e158]
                    - gridcell "04:18 AM" [ref=e159]
                    - gridcell "$100.00" [ref=e160]
                    - gridcell "ActivateOverwrite" [ref=e161]
                    - gridcell [ref=e162]
                  - row "150 04/09/2026 04:18 AM ($200.00) OverwriteAdjust" [ref=e165]:
                    - gridcell "150" [ref=e166]
                    - gridcell "04/09/2026" [ref=e167]
                    - gridcell "04:18 AM" [ref=e168]
                    - gridcell "($200.00)" [ref=e169]
                    - gridcell "OverwriteAdjust" [ref=e170]
                    - gridcell [ref=e171]
                  - row "180 04/08/2026 04:33 AM $100.00 ActivateAddOn" [ref=e174]:
                    - gridcell "180" [ref=e175]
                    - gridcell "04/08/2026" [ref=e176]
                    - gridcell "04:33 AM" [ref=e177]
                    - gridcell "$100.00" [ref=e178]
                    - gridcell "ActivateAddOn" [ref=e179]
                    - gridcell [ref=e180]
                  - row "157 04/08/2026 04:30 AM ($100.00) OverwriteAdjust" [ref=e183]:
                    - gridcell "157" [ref=e184]
                    - gridcell "04/08/2026" [ref=e185]
                    - gridcell "04:30 AM" [ref=e186]
                    - gridcell "($100.00)" [ref=e187]
                    - gridcell "OverwriteAdjust" [ref=e188]
                    - gridcell [ref=e189]
                  - row "157 04/08/2026 04:30 AM $100.00 ActivateOverwrite" [ref=e192]:
                    - gridcell "157" [ref=e193]
                    - gridcell "04/08/2026" [ref=e194]
                    - gridcell "04:30 AM" [ref=e195]
                    - gridcell "$100.00" [ref=e196]
                    - gridcell "ActivateOverwrite" [ref=e197]
                    - gridcell [ref=e198]
                  - row "149 04/08/2026 04:29 AM ($200.00) OverwriteAdjust" [ref=e201]:
                    - gridcell "149" [ref=e202]
                    - gridcell "04/08/2026" [ref=e203]
                    - gridcell "04:29 AM" [ref=e204]
                    - gridcell "($200.00)" [ref=e205]
                    - gridcell "OverwriteAdjust" [ref=e206]
                    - gridcell [ref=e207]
                  - row "149 04/08/2026 04:29 AM $100.00 ActivateOverwrite" [ref=e210]:
                    - gridcell "149" [ref=e211]
                    - gridcell "04/08/2026" [ref=e212]
                    - gridcell "04:29 AM" [ref=e213]
                    - gridcell "$100.00" [ref=e214]
                    - gridcell "ActivateOverwrite" [ref=e215]
                    - gridcell [ref=e216]
                  - row "195 04/07/2026 05:30 AM $100.00 ActivateAddOn" [ref=e219]:
                    - gridcell "195" [ref=e220]
                    - gridcell "04/07/2026" [ref=e221]
                    - gridcell "05:30 AM" [ref=e222]
                    - gridcell "$100.00" [ref=e223]
                    - gridcell "ActivateAddOn" [ref=e224]
                    - gridcell [ref=e225]
        - generic [ref=e232]:
          - generic [ref=e233]:
            - generic [ref=e234]:
              - text: ACTIVITY SUMMARY
              - button [ref=e236] [cursor=pointer]:
                - img [ref=e237]
            - generic [ref=e239]:
              - generic [ref=e240]:
                - term [ref=e241]: ACTIVATED DATE
                - definition [ref=e242]: 01/07/2026
              - generic [ref=e243]:
                - term [ref=e244]: ORIGINAL VALUE
                - definition [ref=e245]: $100.00
              - generic [ref=e246]:
                - term [ref=e247]: LAST REDEEMED DATE
                - definition [ref=e248]: N/A
              - generic [ref=e249]:
                - term [ref=e250]: LAST REDEEMED AMT
                - definition [ref=e251]: $0.00
              - generic [ref=e252]:
                - term [ref=e253]: BALANCE
                - definition [ref=e254]: $100.00
          - generic [ref=e255]:
            - generic [ref=e256]: CURRENTLY VIEWING
            - generic [ref=e257]:
              - generic [ref=e260]:
                - generic [ref=e261]: Gift Card
                - generic [ref=e262]: "4321"
                - generic [ref=e263]:
                  - generic [ref=e264]: "Value:"
                  - generic [ref=e265]: $100.00
                - generic [ref=e266]:
                  - generic [ref=e267]: "Balance:"
                  - generic [ref=e268]: $100.00
              - button "SEARCH ANOTHER" [ref=e270] [cursor=pointer]
        - generic [ref=e271]:
          - generic [ref=e272]: ADJUST
          - generic [ref=e273]:
            - generic [ref=e275]: "0.00"
            - generic [ref=e278]:
              - textbox "Enter Reason ..." [ref=e279]
              - group
            - generic [ref=e281]:
              - generic [ref=e282]:
                - button "1" [ref=e283]:
                  - generic [ref=e284]: "1"
                - button "2" [ref=e285]:
                  - generic [ref=e286]: "2"
                - button "3" [ref=e287]:
                  - generic [ref=e288]: "3"
              - generic [ref=e289]:
                - button "4" [ref=e290]:
                  - generic [ref=e291]: "4"
                - button "5" [ref=e292]:
                  - generic [ref=e293]: "5"
                - button "6" [ref=e294]:
                  - generic [ref=e295]: "6"
              - generic [ref=e296]:
                - button "7" [ref=e297]:
                  - generic [ref=e298]: "7"
                - button "8" [ref=e299]:
                  - generic [ref=e300]: "8"
                - button "9" [ref=e301]:
                  - generic [ref=e302]: "9"
              - generic [ref=e303]:
                - button [ref=e304]
                - button "0" [ref=e306]:
                  - generic [ref=e307]: "0"
                - button [ref=e308]:
                  - img [ref=e309]
            - generic [ref=e311]:
              - button "DECREASE" [disabled]
              - button "INCREASE" [disabled]
  - alert [ref=e312]
```

# Test source

```ts
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
  789 | 		await expect(firstTypeCell).toHaveAttribute('title', new RegExp(type));
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
> 802 | 		await expect(firstAmountCell).toContainText(amount);
      |                                 ^ Error: expect(locator).toContainText(expected) failed
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
  890 | );
  891 | 
  892 | Then(
  893 | 	'I should see the title contain {string} visible',
  894 | 	async ({ page }, name: string) => {
  895 | 		const titleElement = page
  896 | 			.locator('.BalanceLayout__title span')
  897 | 			.getByText(name);
  898 | 
  899 | 		await expect(titleElement).toBeVisible();
  900 | 		await expect(titleElement).toContainText(name);
  901 | 	},
  902 | );
```