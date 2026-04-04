# Instructions

- Following Playwright test failed.
- Explain why, be concise, respect Playwright best practices.
- Provide a snippet of code with the fix, if possible.

# Test info

- Name: departments.feature.spec.js >> Departments management >> Create a new department
- Location: dist/bdd/departments.feature.spec.js:15:3

# Error details

```
Test timeout of 90000ms exceeded.
```

```
Error: locator.click: Test timeout of 90000ms exceeded.
Call log:
  - waiting for locator('input[placeholder="Search…"]')
    - locator resolved to <input value="" id=":r6:" type="search" aria-invalid="false" placeholder="Search…" class="MuiInputBase-input MuiInput-input MuiInputBase-inputTypeSearch MuiInputBase-inputAdornedStart MuiInputBase-inputAdornedEnd css-1mz3u3z"/>
  - attempting click action
    2 × waiting for element to be visible, enabled and stable
      - element is visible, enabled and stable
      - scrolling into view if needed
      - done scrolling
      - <div tabindex="-1" role="presentation" class="MuiDialog-container MuiDialog-scrollPaper css-ekeie0">…</div> from <div role="presentation" class="MuiDialog-root MuiModal-root css-1pqcfvs">…</div> subtree intercepts pointer events
    - retrying click action
    - waiting 20ms
    2 × waiting for element to be visible, enabled and stable
      - element is visible, enabled and stable
      - scrolling into view if needed
      - done scrolling
      - <div tabindex="-1" role="presentation" class="MuiDialog-container MuiDialog-scrollPaper css-ekeie0">…</div> from <div role="presentation" class="MuiDialog-root MuiModal-root css-1pqcfvs">…</div> subtree intercepts pointer events
    - retrying click action
      - waiting 100ms
    171 × waiting for element to be visible, enabled and stable
        - element is visible, enabled and stable
        - scrolling into view if needed
        - done scrolling
        - <div tabindex="-1" role="presentation" class="MuiDialog-container MuiDialog-scrollPaper css-ekeie0">…</div> from <div role="presentation" class="MuiDialog-root MuiModal-root css-1pqcfvs">…</div> subtree intercepts pointer events
      - retrying click action
        - waiting 500ms

```

# Page snapshot

```yaml
- generic [ref=e1]:
  - generic [ref=e4]:
    - banner [ref=e5]:
      - generic [ref=e6]:
        - img [ref=e9] [cursor=pointer]
        - paragraph [ref=e12]: Departments
        - generic [ref=e13]:
          - generic [ref=e15] [cursor=pointer]:
            - paragraph [ref=e16]: 05:50 AM
            - generic [ref=e20]:
              - paragraph [ref=e21]: Apr
              - paragraph [ref=e22]: "04"
          - generic [ref=e25] [cursor=pointer]:
            - list [ref=e26]:
              - listitem [ref=e27]:
                - generic [ref=e28]: BLUE SALON
              - listitem [ref=e29]:
                - generic [ref=e30]: 1032 YONKERS AVE
                - paragraph [ref=e32]: Yonkers, NY, 10704 | (707) 707-1122
                - generic [ref=e33]: "Pos Blue | Station: 1"
            - img [ref=e35]
    - paragraph [ref=e41]: © 2026 XSoftware - 2025.12
    - main [ref=e42]:
      - generic [ref=e43]:
        - generic [ref=e45]:
          - generic [ref=e48]:
            - img [ref=e49]
            - searchbox [ref=e51]
          - grid [ref=e52]:
            - generic [ref=e53]:
              - row [ref=e54]:
                - columnheader [ref=e55] [cursor=pointer]:
                  - generic [ref=e57]: Department Name
                - columnheader [ref=e58] [cursor=pointer]:
                  - generic [ref=e60]: Department Type
                - columnheader [ref=e61] [cursor=pointer]:
                  - generic [ref=e63]: Non-Inventory
                - columnheader [ref=e64] [cursor=pointer]:
                  - generic [ref=e66]: Created At
                - columnheader [ref=e67] [cursor=pointer]:
                  - generic [ref=e69]: Created By
                - columnheader [ref=e70]:
                  - generic [ref=e72]: Actions
              - rowgroup [ref=e73]:
                - row [ref=e74]:
                  - gridcell [ref=e75]: Pedicure & Manicure
                  - gridcell [ref=e76]: Service
                  - gridcell [ref=e77]:
                    - img [ref=e79]
                  - gridcell [ref=e81]: 03/10/2026 10:17 PM
                  - gridcell [ref=e82]: pos.blue@galaxyaccess.us
                  - gridcell [ref=e83]:
                    - menu [ref=e84]:
                      - menuitem [ref=e85] [cursor=pointer]:
                        - img [ref=e86]
                      - menuitem [ref=e88] [cursor=pointer]:
                        - img [ref=e89]
                      - menuitem [ref=e91] [cursor=pointer]:
                        - img [ref=e92]
                - row [ref=e94]:
                  - gridcell [ref=e95]: Massage
                  - gridcell [ref=e96]: Service
                  - gridcell [ref=e97]:
                    - img [ref=e99]
                  - gridcell [ref=e101]: 01/07/2026 09:15 PM
                  - gridcell [ref=e102]: techsupport.lv1@galaxyaccess.us
                  - gridcell [ref=e103]:
                    - menu [ref=e104]:
                      - menuitem [ref=e105] [cursor=pointer]:
                        - img [ref=e106]
                      - menuitem [ref=e108] [cursor=pointer]:
                        - img [ref=e109]
                      - menuitem [ref=e111] [cursor=pointer]:
                        - img [ref=e112]
                - row [ref=e114]:
                  - gridcell [ref=e115]: Facial
                  - gridcell [ref=e116]: Service
                  - gridcell [ref=e117]:
                    - img [ref=e119]
                  - gridcell [ref=e121]: 01/07/2026 09:15 PM
                  - gridcell [ref=e122]: techsupport.lv1@galaxyaccess.us
                  - gridcell [ref=e123]:
                    - menu [ref=e124]:
                      - menuitem [ref=e125] [cursor=pointer]:
                        - img [ref=e126]
                      - menuitem [ref=e128] [cursor=pointer]:
                        - img [ref=e129]
                      - menuitem [ref=e131] [cursor=pointer]:
                        - img [ref=e132]
                - row [ref=e134]:
                  - gridcell [ref=e135]: Waxing
                  - gridcell [ref=e136]: Service
                  - gridcell [ref=e137]:
                    - img [ref=e139]
                  - gridcell [ref=e141]: 01/07/2026 09:15 PM
                  - gridcell [ref=e142]: techsupport.lv1@galaxyaccess.us
                  - gridcell [ref=e143]:
                    - menu [ref=e144]:
                      - menuitem [ref=e145] [cursor=pointer]:
                        - img [ref=e146]
                      - menuitem [ref=e148] [cursor=pointer]:
                        - img [ref=e149]
                      - menuitem [ref=e151] [cursor=pointer]:
                        - img [ref=e152]
                - row [ref=e154]:
                  - gridcell [ref=e155]: Eyelash
                  - gridcell [ref=e156]: Service
                  - gridcell [ref=e157]:
                    - img [ref=e159]
                  - gridcell [ref=e161]: 01/07/2026 09:15 PM
                  - gridcell [ref=e162]: techsupport.lv1@galaxyaccess.us
                  - gridcell [ref=e163]:
                    - menu [ref=e164]:
                      - menuitem [ref=e165] [cursor=pointer]:
                        - img [ref=e166]
                      - menuitem [ref=e168] [cursor=pointer]:
                        - img [ref=e169]
                      - menuitem [ref=e171] [cursor=pointer]:
                        - img [ref=e172]
                - row [ref=e174]:
                  - gridcell [ref=e175]: Product
                  - gridcell [ref=e176]: Product
                  - gridcell [ref=e177]:
                    - img [ref=e179]
                  - gridcell [ref=e181]: 01/07/2026 09:15 PM
                  - gridcell [ref=e182]: techsupport.lv1@galaxyaccess.us
                  - gridcell [ref=e183]:
                    - menu [ref=e184]:
                      - menuitem [ref=e185] [cursor=pointer]:
                        - img [ref=e186]
                      - menuitem [ref=e188] [cursor=pointer]:
                        - img [ref=e189]
                      - menuitem [ref=e191] [cursor=pointer]:
                        - img [ref=e192]
                - row [ref=e194]:
                  - gridcell [ref=e195]: Hair
                  - gridcell [ref=e196]: Service
                  - gridcell [ref=e197]:
                    - img [ref=e199]
                  - gridcell [ref=e201]: 01/07/2026 09:15 PM
                  - gridcell [ref=e202]: techsupport.lv1@galaxyaccess.us
                  - gridcell [ref=e203]:
                    - menu [ref=e204]:
                      - menuitem [ref=e205] [cursor=pointer]:
                        - img [ref=e206]
                      - menuitem [ref=e208] [cursor=pointer]:
                        - img [ref=e209]
                      - menuitem [ref=e211] [cursor=pointer]:
                        - img [ref=e212]
                - row [ref=e214]:
                  - gridcell [ref=e215]: Nails
                  - gridcell [ref=e216]: Service
                  - gridcell [ref=e217]:
                    - img [ref=e219]
                  - gridcell [ref=e221]: 01/07/2026 09:15 PM
                  - gridcell [ref=e222]: techsupport.lv1@galaxyaccess.us
                  - gridcell [ref=e223]:
                    - menu [ref=e224]:
                      - menuitem [ref=e225] [cursor=pointer]:
                        - img [ref=e226]
                      - menuitem [ref=e228] [cursor=pointer]:
                        - img [ref=e229]
                      - menuitem [ref=e231] [cursor=pointer]:
                        - img [ref=e232]
          - generic [ref=e236]:
            - text: 0.00 s
            - generic [ref=e238]:
              - paragraph [ref=e239]: "Rows per page:"
              - generic [ref=e240]:
                - combobox [ref=e241] [cursor=pointer]: "20"
                - textbox: "20"
                - img
              - paragraph [ref=e242]: 1–8 of 8
              - generic [ref=e243]:
                - button [disabled]:
                  - img
                - button [disabled]:
                  - img
        - generic [ref=e244]:
          - button [ref=e245] [cursor=pointer]:
            - img [ref=e247]
            - text: Refresh
          - button [ref=e249] [cursor=pointer]:
            - img [ref=e251]
            - text: Add New
  - alert [ref=e253]
  - dialog "Create New Department close" [ref=e256]:
    - heading "Create New Department close" [level=2] [ref=e257]:
      - text: Create New Department
      - button "close" [ref=e258] [cursor=pointer]:
        - img [ref=e259]
    - generic [ref=e261]:
      - generic [ref=e262]:
        - generic [ref=e264]:
          - generic [ref=e265]:
            - text: Department Name
            - generic [ref=e266]: "*"
          - generic [ref=e267]:
            - textbox "Department Name" [ref=e268]: Pedicure & Manicure
            - group:
              - generic: Department Name *
        - generic [ref=e270]:
          - generic [ref=e271]:
            - text: Department Type
            - generic [ref=e272]: "*"
          - generic [ref=e273]:
            - combobox "Department Type Service" [ref=e274] [cursor=pointer]:
              - generic [ref=e276]: Service
            - textbox: Service
            - img
            - group:
              - generic: Department Type *
        - group [ref=e279]:
          - generic [ref=e280] [cursor=pointer]:
            - checkbox "Non-Inventory" [ref=e283]
            - generic [ref=e286]: Non-Inventory
      - generic [ref=e287]:
        - button "Save" [ref=e288] [cursor=pointer]:
          - img [ref=e290]
          - text: Save
        - button "Cancel" [ref=e292] [cursor=pointer]:
          - img [ref=e294]
          - text: Cancel
```

# Test source

```ts
  2955 | 		await expect(divider).toBeVisible();
  2956 | 		await expect(divider.locator('span.item-divider')).toHaveText(text);
  2957 | 	},
  2958 | );
  2959 | 
  2960 | Then(
  2961 | 	'I should see the Reg Pay, NC Tip, Commission as {string} in employee view',
  2962 | 	async ({ page }, expectedValues: string) => {
  2963 | 		const values = expectedValues.split(' ');
  2964 | 		expect(values).toHaveLength(3);
  2965 | 
  2966 | 		const [regPay, ncTip, commission] = values;
  2967 | 
  2968 | 		const detailsTable = page.locator('table.details-payroll');
  2969 | 		const dataRow = detailsTable.locator('tbody tr').nth(1);
  2970 | 
  2971 | 		await expect(dataRow).toBeVisible();
  2972 | 
  2973 | 		// const totalSalesCell = dataRow.locator('td').nth(2);
  2974 | 		const regPayCell = dataRow.locator('td').nth(3);
  2975 | 		const ncTipCell = dataRow.locator('td').nth(4);
  2976 | 		const commissionCell = dataRow.locator('td').nth(5);
  2977 | 
  2978 | 		// await expect(totalSalesCell).toHaveText(regHrs);
  2979 | 		await expect(regPayCell).toHaveText(regPay);
  2980 | 		await expect(ncTipCell).toHaveText(ncTip);
  2981 | 		await expect(commissionCell).toHaveText(commission);
  2982 | 	},
  2983 | );
  2984 | 
  2985 | Then(
  2986 | 	'I should see the Total Sales, Net Comm, NC Tip, Total Payout as {string} in employee view',
  2987 | 	async ({ page }, expectedValues: string) => {
  2988 | 		const values = expectedValues.split(' ');
  2989 | 		expect(values).toHaveLength(4);
  2990 | 
  2991 | 		const [totalSales, netComm, ncTip, totalPayout] = values;
  2992 | 
  2993 | 		const detailsTable = page.locator('table.details-payroll');
  2994 | 		const dataRow = detailsTable.locator('tbody tr').nth(1);
  2995 | 
  2996 | 		await expect(dataRow).toBeVisible();
  2997 | 
  2998 | 		const totalSalesCell = dataRow.locator('td').nth(2);
  2999 | 		const netCommCell = dataRow.locator('td').nth(3);
  3000 | 		const ncTipCell = dataRow.locator('td').nth(4);
  3001 | 		const totalPayoutCell = dataRow.locator('td').nth(5);
  3002 | 
  3003 | 		await expect(totalSalesCell).toHaveText(totalSales);
  3004 | 		await expect(netCommCell).toHaveText(netComm);
  3005 | 		await expect(ncTipCell).toHaveText(ncTip);
  3006 | 		await expect(totalPayoutCell).toHaveText(totalPayout);
  3007 | 	},
  3008 | );
  3009 | 
  3010 | When('I fill the department name {string}', async ({ page }, name: string) => {
  3011 | 	const dialog = page.getByRole('dialog');
  3012 | 
  3013 | 	const input = dialog.locator('input[name="name"]');
  3014 | 
  3015 | 	await expect(input).toBeVisible();
  3016 | 	await expect(input).toBeEnabled();
  3017 | 
  3018 | 	await input.fill(name);
  3019 | 	await expect(input).toHaveValue(name);
  3020 | });
  3021 | 
  3022 | When('I select department type {string}', async ({ page }, type: string) => {
  3023 | 	const dialog = page.getByRole('dialog');
  3024 | 
  3025 | 	const dropdown = dialog.getByRole('combobox', {
  3026 | 		name: /department type/i,
  3027 | 	});
  3028 | 
  3029 | 	await expect(dropdown).toBeVisible();
  3030 | 	await dropdown.click();
  3031 | 
  3032 | 	const option = page.getByRole('option', {
  3033 | 		name: new RegExp(`^${type}$`, 'i'),
  3034 | 	});
  3035 | 
  3036 | 	await expect(option).toBeVisible();
  3037 | 	await option.click();
  3038 | 
  3039 | 	await expect(dropdown).toHaveText(new RegExp(type, 'i'));
  3040 | });
  3041 | 
  3042 | When('I click on refresh department', async ({ page }) => {
  3043 | 	await page.locator('[data-testid="ReplayIcon"]').click();
  3044 | });
  3045 | 
  3046 | When(
  3047 | 	'I search department with keyword {string} and expect {int} results',
  3048 | 	async ({ page }, keyword: string, count: number) => {
  3049 | 		const input = page.locator('input[placeholder="Search…"]');
  3050 | 		const rows = page.locator('.MuiDataGrid-row');
  3051 | 
  3052 | 		await expect(input).toBeVisible();
  3053 | 
  3054 | 		await input.fill('');
> 3055 | 		await input.click();
       |               ^ Error: locator.click: Test timeout of 90000ms exceeded.
  3056 | 		await page.keyboard.type(keyword, { delay: 30 });
  3057 | 
  3058 | 		await expect(rows).toHaveCount(count);
  3059 | 	},
  3060 | );
  3061 | 
  3062 | When(
  3063 | 	'I click the {string} button in the dialog',
  3064 | 	async ({ page }, text: string) => {
  3065 | 		await page
  3066 | 			.getByRole('dialog')
  3067 | 			.getByRole('button', { name: new RegExp(`^${text}$`, 'i') })
  3068 | 			.click();
  3069 | 	},
  3070 | );
  3071 | 
  3072 | When(
  3073 | 	'I double click on the department row {string}',
  3074 | 	async ({ page }, departmentName: string) => {
  3075 | 		const nameCell = page.locator(
  3076 | 			`.MuiDataGrid-cell[data-field="name"]:has-text("${departmentName}")`,
  3077 | 		);
  3078 | 
  3079 | 		await expect(nameCell).toBeVisible();
  3080 | 		await nameCell.dblclick();
  3081 | 	},
  3082 | );
  3083 | 
  3084 | When('I clear department search', async ({ page }) => {
  3085 | 	const input = page.locator('input[placeholder="Search…"]');
  3086 | 	await input.fill('');
  3087 | 	await input.dispatchEvent('input');
  3088 | });
  3089 | 
  3090 | Then(
  3091 | 	'I should see department {string} in the list',
  3092 | 	async ({ page }, name: string) => {
  3093 | 		const departmentCell = page
  3094 | 			.locator('.MuiDataGrid-row')
  3095 | 			.locator('[data-field="name"]', { hasText: name })
  3096 | 			.first();
  3097 | 
  3098 | 		await expect(departmentCell).toBeVisible();
  3099 | 		await expect(departmentCell).toContainText(name);
  3100 | 	},
  3101 | );
  3102 | 
  3103 | Then('I should see the default filter set to Today', async ({ page }) => {
  3104 | 	const rangeDateCell = page.locator('p.pageDetail');
  3105 | 
  3106 | 	const formattedToday = await page.evaluate(() => {
  3107 | 		const today = new Date();
  3108 | 		return today.toLocaleDateString('en-US', {
  3109 | 			year: 'numeric',
  3110 | 			month: '2-digit',
  3111 | 			day: '2-digit',
  3112 | 		});
  3113 | 	});
  3114 | 
  3115 | 	await expect(rangeDateCell).toBeVisible();
  3116 | 	await expect(rangeDateCell).toHaveText(
  3117 | 		`${formattedToday} - ${formattedToday}`,
  3118 | 	);
  3119 | });
  3120 | 
  3121 | Then(
  3122 | 	'I should see the text {string} in the payroll summary',
  3123 | 	async ({ page }, text: string) => {
  3124 | 		const payrollSummary = page.locator('div.summary-title');
  3125 | 
  3126 | 		await expect(payrollSummary).toBeVisible();
  3127 | 		await expect(payrollSummary).toHaveText(text);
  3128 | 	},
  3129 | );
  3130 | 
  3131 | Then(
  3132 | 	'I should not see department {string} in the list',
  3133 | 	async ({ page }, name: string) => {
  3134 | 		const departmentCell = page
  3135 | 			.locator('.MuiDataGrid-row')
  3136 | 			.locator('[data-field="name"]', { hasText: name });
  3137 | 
  3138 | 		await expect(departmentCell).toHaveCount(0);
  3139 | 	},
  3140 | );
  3141 | 
  3142 | Then('department type should be {string}', async ({ page }, type: string) => {
  3143 | 	const deptTypeCell = page
  3144 | 		.locator('.MuiDataGrid-row')
  3145 | 		.first()
  3146 | 		.locator('[data-field="deptType"]');
  3147 | 
  3148 | 	await expect(deptTypeCell).toContainText(type);
  3149 | });
  3150 | 
  3151 | Then('I should see the department edit dialog', async ({ page }) => {
  3152 | 	await expect(page.getByRole('dialog')).toBeVisible();
  3153 | });
  3154 | 
  3155 | Then(
```