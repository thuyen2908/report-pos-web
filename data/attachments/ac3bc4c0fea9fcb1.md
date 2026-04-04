# Instructions

- Following Playwright test failed.
- Explain why, be concise, respect Playwright best practices.
- Provide a snippet of code with the fix, if possible.

# Test info

- Name: tickets.feature.spec.js >> Reopen tickets >> Update gift card balance correctly after voiding a gift card payment and paying with cash
- Location: dist/bdd/tickets.feature.spec.js:643:3

# Error details

```
Error: expect(locator).not.toContainText(expected) failed

Locator: locator('.MuiDataGrid-row').first().locator('.MuiDataGrid-cell[data-field="createdAt"]')
Expected substring: not "04/04/2026"
Received string: "04/04/2026"
Timeout: 30000ms

Call log:
  - Expect "not toContainText" with timeout 30000ms
  - waiting for locator('.MuiDataGrid-row').first().locator('.MuiDataGrid-cell[data-field="createdAt"]')
    34 × locator resolved to <div tabindex="-1" role="gridcell" aria-colspan="1" data-colindex="1" aria-colindex="2" title="04/04/2026" data-field="createdAt" class="MuiDataGrid-cell MuiDataGrid-cell--textLeft">04/04/2026</div>
       - unexpected value "04/04/2026"

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
            - paragraph [ref=e66]: 07:21 AM
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
                  - row "192 04/04/2026 05:51 AM ($17.50) Redeem" [ref=e129]:
                    - gridcell "192" [ref=e130]
                    - gridcell "04/04/2026" [ref=e131]
                    - gridcell "05:51 AM" [ref=e132]
                    - gridcell "($17.50)" [ref=e133]
                    - gridcell "Redeem" [ref=e134]
                    - gridcell [ref=e135]
                  - row "0 03/03/2026 04:25 AM $100.00 ActivateNew" [ref=e138]:
                    - gridcell "0" [ref=e139]
                    - gridcell "03/03/2026" [ref=e140]
                    - gridcell "04:25 AM" [ref=e141]
                    - gridcell "$100.00" [ref=e142]
                    - gridcell "ActivateNew" [ref=e143]
                    - gridcell [ref=e144]
        - generic [ref=e150]:
          - generic [ref=e151]:
            - generic [ref=e152]:
              - text: ACTIVITY SUMMARY
              - button [ref=e154] [cursor=pointer]:
                - img [ref=e155]
            - generic [ref=e157]:
              - generic [ref=e158]:
                - term [ref=e159]: ACTIVATED DATE
                - definition [ref=e160]: 03/03/2026
              - generic [ref=e161]:
                - term [ref=e162]: ORIGINAL VALUE
                - definition [ref=e163]: $100.00
              - generic [ref=e164]:
                - term [ref=e165]: LAST REDEEMED DATE
                - definition [ref=e166]: 04/04/2026
              - generic [ref=e167]:
                - term [ref=e168]: LAST REDEEMED AMT
                - definition [ref=e169]: $0.00
              - generic [ref=e170]:
                - term [ref=e171]: BALANCE
                - definition [ref=e172]: $82.50
          - generic [ref=e173]:
            - generic [ref=e174]: CURRENTLY VIEWING
            - generic [ref=e175]:
              - generic [ref=e178]:
                - generic [ref=e179]: Gift Card
                - generic [ref=e180]: "1003"
                - generic [ref=e181]:
                  - generic [ref=e182]: "Value:"
                  - generic [ref=e183]: $100.00
                - generic [ref=e184]:
                  - generic [ref=e185]: "Balance:"
                  - generic [ref=e186]: $82.50
              - button "SEARCH ANOTHER" [ref=e188] [cursor=pointer]
        - generic [ref=e189]:
          - generic [ref=e190]: ADJUST
          - generic [ref=e191]:
            - generic [ref=e193]: "0.00"
            - generic [ref=e196]:
              - textbox "Enter Reason ..." [ref=e197]
              - group
            - generic [ref=e199]:
              - generic [ref=e200]:
                - button "1" [ref=e201]:
                  - generic [ref=e202]: "1"
                - button "2" [ref=e203]:
                  - generic [ref=e204]: "2"
                - button "3" [ref=e205]:
                  - generic [ref=e206]: "3"
              - generic [ref=e207]:
                - button "4" [ref=e208]:
                  - generic [ref=e209]: "4"
                - button "5" [ref=e210]:
                  - generic [ref=e211]: "5"
                - button "6" [ref=e212]:
                  - generic [ref=e213]: "6"
              - generic [ref=e214]:
                - button "7" [ref=e215]:
                  - generic [ref=e216]: "7"
                - button "8" [ref=e217]:
                  - generic [ref=e218]: "8"
                - button "9" [ref=e219]:
                  - generic [ref=e220]: "9"
              - generic [ref=e221]:
                - button [ref=e222]
                - button "0" [ref=e224]:
                  - generic [ref=e225]: "0"
                - button [ref=e226]:
                  - img [ref=e227]
            - generic [ref=e229]:
              - button "DECREASE" [disabled]
              - button "INCREASE" [disabled]
  - alert [ref=e230]
```

# Test source

```ts
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
> 840 | 		await expect(firstDateCell).not.toContainText(formattedToday);
      |                                   ^ Error: expect(locator).not.toContainText(expected) failed
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
  903 | 
  904 | Then(
  905 | 	'I should see the {string} option is checked',
  906 | 	async ({ page }, name: string) => {
  907 | 		const radioButton = page.getByLabel(name);
  908 | 
  909 | 		await expect(radioButton).toBeChecked();
  910 | 	},
  911 | );
  912 | 
  913 | When('I select the discount {string}', async ({ page }, discount: string) => {
  914 | 	const discountElement = page
  915 | 		.locator('.MuiListItem-gutters')
  916 | 		.getByText(discount, { exact: true });
  917 | 	await expect(discountElement).toHaveText(discount);
  918 | 	await discountElement.click();
  919 | });
  920 | 
  921 | When('I select the type {string} option', async ({ page }, type: string) => {
  922 | 	const typeElement = page.locator('.xFlex-select');
  923 | 	await typeElement.click();
  924 | 	await page.locator('#menu-typeDiscount').getByText(type).click();
  925 | });
  926 | 
  927 | Then(
  928 | 	'I should see the discount type {string} visible',
  929 | 	async ({ page }, type: string) => {
  930 | 		const discountTypeElement = page
  931 | 			.locator('.MuiListItemText-primary')
  932 | 			.first()
  933 | 			.getByText(type);
  934 | 		await expect(discountTypeElement).toHaveText(type);
  935 | 	},
  936 | );
  937 | 
  938 | When(
  939 | 	'I enter the discount amount {string}',
  940 | 	async ({ page }, amount: string) => {
```