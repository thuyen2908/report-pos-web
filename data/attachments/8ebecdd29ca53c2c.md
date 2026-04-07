# Instructions

- Following Playwright test failed.
- Explain why, be concise, respect Playwright best practices.
- Provide a snippet of code with the fix, if possible.

# Test info

- Name: create-tickets.feature.spec.js >> Create tickets >> Queue - show Total, Last Service, Clock In Time
- Location: dist/bdd/create-tickets.feature.spec.js:975:3

# Error details

```
Error: expect(locator).toBeVisible() failed

Locator: locator('ul.ListItemEmployee__wrap').first().locator('li.xEmployeeItem').filter({ hasText: 'Ciara' }).locator('.xEmployeeItem__wrap .MuiChip-root').filter({ hasText: 'T: 20.11' })
Expected: visible
Timeout: 30000ms
Error: element(s) not found

Call log:
  - Expect "toBeVisible" with timeout 30000ms
  - waiting for locator('ul.ListItemEmployee__wrap').first().locator('li.xEmployeeItem').filter({ hasText: 'Ciara' }).locator('.xEmployeeItem__wrap .MuiChip-root').filter({ hasText: 'T: 20.11' })

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
            - paragraph [ref=e66]: 05:33 AM
            - generic [ref=e70]:
              - paragraph [ref=e71]: Apr
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
          - generic [ref=e95]:
            - generic [ref=e97]:
              - generic:
                - img
              - tablist [ref=e100]:
                - tab "NAILS" [selected] [ref=e101] [cursor=pointer]:
                  - generic [ref=e102]: NAILS
                - tab "HAIR" [ref=e103] [cursor=pointer]:
                  - generic [ref=e104]: HAIR
              - generic:
                - img
            - tabpanel [ref=e106]:
              - list [ref=e107]:
                - listitem [ref=e108] [cursor=pointer]:
                  - img [ref=e109]
                - listitem [ref=e112] [cursor=pointer]:
                  - img [ref=e113]
              - list [ref=e116]:
                - listitem [ref=e117] [cursor=pointer]:
                  - generic [ref=e118]:
                    - generic [ref=e120]: W
                    - generic [ref=e121]:
                      - generic [ref=e123]: "#1"
                      - generic [ref=e124]: WorkSlipAdjustTip2
                  - generic [ref=e126]:
                    - generic [ref=e127]:
                      - img [ref=e128]
                      - generic [ref=e130]: 12:00 AM
                    - generic [ref=e131]:
                      - img [ref=e132]
                      - generic [ref=e134]: "Turn: 0.0"
                    - generic [ref=e135]:
                      - img [ref=e136]
                      - generic [ref=e141]: "T: 0.00"
                    - generic [ref=e142]:
                      - img [ref=e143]
                      - generic [ref=e147]: "L: 0.00"
                - listitem [ref=e148] [cursor=pointer]:
                  - generic [ref=e149]:
                    - generic [ref=e151]: Z
                    - generic [ref=e152]:
                      - generic [ref=e154]: "#2"
                      - generic [ref=e155]: Zoey
                  - generic [ref=e157]:
                    - generic [ref=e158]:
                      - img [ref=e159]
                      - generic [ref=e161]: 12:00 AM
                    - generic [ref=e162]:
                      - img [ref=e163]
                      - generic [ref=e165]: "Turn: 0.0"
                    - generic [ref=e166]:
                      - img [ref=e167]
                      - generic [ref=e172]: "T: 0.00"
                    - generic [ref=e173]:
                      - img [ref=e174]
                      - generic [ref=e178]: "L: 0.00"
                - listitem [ref=e179] [cursor=pointer]:
                  - generic [ref=e180]:
                    - generic [ref=e182]: V
                    - generic [ref=e183]:
                      - generic [ref=e185]: "#3"
                      - generic [ref=e186]: Venus
                  - generic [ref=e188]:
                    - generic [ref=e189]:
                      - img [ref=e190]
                      - generic [ref=e192]: 05:19 AM
                    - generic [ref=e193]:
                      - img [ref=e194]
                      - generic [ref=e196]: "Turn: 0.0"
                    - generic [ref=e197]:
                      - img [ref=e198]
                      - generic [ref=e203]: "T: 0.00"
                    - generic [ref=e204]:
                      - img [ref=e205]
                      - generic [ref=e209]: "L: 0.00"
                - listitem [ref=e210] [cursor=pointer]:
                  - generic [ref=e211]:
                    - generic [ref=e213]: S
                    - generic [ref=e214]:
                      - generic [ref=e216]: "#4"
                      - generic [ref=e217]: Serena
                  - generic [ref=e219]:
                    - generic [ref=e220]:
                      - img [ref=e221]
                      - generic [ref=e223]: 05:22 AM
                    - generic [ref=e224]:
                      - img [ref=e225]
                      - generic [ref=e227]: "Turn: 0.0"
                    - generic [ref=e228]:
                      - img [ref=e229]
                      - generic [ref=e234]: "T: 0.00"
                    - generic [ref=e235]:
                      - img [ref=e236]
                      - generic [ref=e240]: "L: 0.00"
                - listitem [ref=e241] [cursor=pointer]:
                  - generic [ref=e242]:
                    - generic [ref=e244]: E
                    - generic [ref=e245]:
                      - generic [ref=e247]: "#5"
                      - generic [ref=e248]: Elena
                  - generic [ref=e250]:
                    - generic [ref=e251]:
                      - img [ref=e252]
                      - generic [ref=e254]: 05:22 AM
                    - generic [ref=e255]:
                      - img [ref=e256]
                      - generic [ref=e258]: "Turn: 0.0"
                    - generic [ref=e259]:
                      - img [ref=e260]
                      - generic [ref=e265]: "T: 0.00"
                    - generic [ref=e266]:
                      - img [ref=e267]
                      - generic [ref=e271]: "L: 0.00"
                - listitem [ref=e272] [cursor=pointer]:
                  - generic [ref=e273]:
                    - generic [ref=e275]: G
                    - generic [ref=e276]:
                      - generic [ref=e278]: "#6"
                      - generic [ref=e279]: Gemma
                  - generic [ref=e281]:
                    - generic [ref=e282]:
                      - img [ref=e283]
                      - generic [ref=e285]: 05:23 AM
                    - generic [ref=e286]:
                      - img [ref=e287]
                      - generic [ref=e289]: "Turn: 0.0"
                    - generic [ref=e290]:
                      - img [ref=e291]
                      - generic [ref=e296]: "T: 0.00"
                    - generic [ref=e297]:
                      - img [ref=e298]
                      - generic [ref=e302]: "L: 0.00"
                - listitem [ref=e303] [cursor=pointer]:
                  - generic [ref=e304]:
                    - generic [ref=e306]: C
                    - generic [ref=e307]:
                      - generic [ref=e309]: "#7"
                      - generic [ref=e310]: Calantha
                  - generic [ref=e312]:
                    - generic [ref=e313]:
                      - img [ref=e314]
                      - generic [ref=e316]: 05:23 AM
                    - generic [ref=e317]:
                      - img [ref=e318]
                      - generic [ref=e320]: "Turn: 0.0"
                    - generic [ref=e321]:
                      - img [ref=e322]
                      - generic [ref=e327]: "T: 0.00"
                    - generic [ref=e328]:
                      - img [ref=e329]
                      - generic [ref=e333]: "L: 0.00"
                - listitem [ref=e334] [cursor=pointer]:
                  - generic [ref=e335]:
                    - generic [ref=e337]: H
                    - generic [ref=e338]:
                      - generic [ref=e340]: "#8"
                      - generic [ref=e341]: Hilary
                  - generic [ref=e343]:
                    - generic [ref=e344]:
                      - img [ref=e345]
                      - generic [ref=e347]: 05:26 AM
                    - generic [ref=e348]:
                      - img [ref=e349]
                      - generic [ref=e351]: "Turn: 0.0"
                    - generic [ref=e352]:
                      - img [ref=e353]
                      - generic [ref=e358]: "T: 0.00"
                    - generic [ref=e359]:
                      - img [ref=e360]
                      - generic [ref=e364]: "L: 0.00"
                - listitem [ref=e365] [cursor=pointer]:
                  - generic [ref=e366]:
                    - generic [ref=e368]: V
                    - generic [ref=e369]:
                      - generic [ref=e371]: "#9"
                      - generic [ref=e372]: Valerie
                  - generic [ref=e374]:
                    - generic [ref=e375]:
                      - img [ref=e376]
                      - generic [ref=e378]: 05:26 AM
                    - generic [ref=e379]:
                      - img [ref=e380]
                      - generic [ref=e382]: "Turn: 0.0"
                    - generic [ref=e383]:
                      - img [ref=e384]
                      - generic [ref=e389]: "T: 0.00"
                    - generic [ref=e390]:
                      - img [ref=e391]
                      - generic [ref=e395]: "L: 0.00"
                - listitem [ref=e396] [cursor=pointer]:
                  - generic [ref=e397]:
                    - generic [ref=e399]: M
                    - generic [ref=e400]:
                      - generic [ref=e402]: "#10"
                      - generic [ref=e403]: Madison
                  - generic [ref=e405]:
                    - generic [ref=e406]:
                      - img [ref=e407]
                      - generic [ref=e409]: 05:28 AM
                    - generic [ref=e410]:
                      - img [ref=e411]
                      - generic [ref=e413]: "Turn: 0.0"
                    - generic [ref=e414]:
                      - img [ref=e415]
                      - generic [ref=e420]: "T: 0.00"
                    - generic [ref=e421]:
                      - img [ref=e422]
                      - generic [ref=e426]: "L: 0.00"
                - listitem [ref=e427] [cursor=pointer]:
                  - generic [ref=e428]:
                    - generic [ref=e430]: A
                    - generic [ref=e431]:
                      - generic [ref=e433]: "#11"
                      - generic [ref=e434]: Aubrey
                  - generic [ref=e436]:
                    - generic [ref=e437]:
                      - img [ref=e438]
                      - generic [ref=e440]: 05:28 AM
                    - generic [ref=e441]:
                      - img [ref=e442]
                      - generic [ref=e444]: "Turn: 0.0"
                    - generic [ref=e445]:
                      - img [ref=e446]
                      - generic [ref=e451]: "T: 0.00"
                    - generic [ref=e452]:
                      - img [ref=e453]
                      - generic [ref=e457]: "L: 0.00"
                - listitem [ref=e458] [cursor=pointer]:
                  - generic [ref=e459]:
                    - generic [ref=e461]: L
                    - generic [ref=e462]:
                      - generic [ref=e464]: "#12"
                      - generic [ref=e465]: Lauren
                  - generic [ref=e467]:
                    - generic [ref=e468]:
                      - img [ref=e469]
                      - generic [ref=e471]: 05:29 AM
                    - generic [ref=e472]:
                      - img [ref=e473]
                      - generic [ref=e475]: "Turn: 0.0"
                    - generic [ref=e476]:
                      - img [ref=e477]
                      - generic [ref=e482]: "T: 0.00"
                    - generic [ref=e483]:
                      - img [ref=e484]
                      - generic [ref=e488]: "L: 0.00"
                - listitem [ref=e489] [cursor=pointer]:
                  - generic [ref=e490]:
                    - generic [ref=e492]: D
                    - generic [ref=e493]:
                      - generic [ref=e495]: "#13"
                      - generic [ref=e496]: Daisy
                  - generic [ref=e498]:
                    - generic [ref=e499]:
                      - img [ref=e500]
                      - generic [ref=e502]: 05:29 AM
                    - generic [ref=e503]:
                      - img [ref=e504]
                      - generic [ref=e506]: "Turn: 0.0"
                    - generic [ref=e507]:
                      - img [ref=e508]
                      - generic [ref=e513]: "T: 0.00"
                    - generic [ref=e514]:
                      - img [ref=e515]
                      - generic [ref=e519]: "L: 0.00"
                - listitem [ref=e520] [cursor=pointer]:
                  - generic [ref=e521]:
                    - generic [ref=e523]: P
                    - generic [ref=e524]:
                      - generic [ref=e526]: "#14"
                      - generic [ref=e527]: Paige
                  - generic [ref=e529]:
                    - generic [ref=e530]:
                      - img [ref=e531]
                      - generic [ref=e533]: 05:30 AM
                    - generic [ref=e534]:
                      - img [ref=e535]
                      - generic [ref=e537]: "Turn: 0.0"
                    - generic [ref=e538]:
                      - img [ref=e539]
                      - generic [ref=e544]: "T: 0.00"
                    - generic [ref=e545]:
                      - img [ref=e546]
                      - generic [ref=e550]: "L: 0.00"
                - listitem [ref=e551] [cursor=pointer]:
                  - generic [ref=e552]:
                    - generic [ref=e554]: I
                    - generic [ref=e555]:
                      - generic [ref=e557]: "#15"
                      - generic [ref=e558]: Isabella
                  - generic [ref=e560]:
                    - generic [ref=e561]:
                      - img [ref=e562]
                      - generic [ref=e564]: 05:30 AM
                    - generic [ref=e565]:
                      - img [ref=e566]
                      - generic [ref=e568]: "Turn: 0.0"
                    - generic [ref=e569]:
                      - img [ref=e570]
                      - generic [ref=e575]: "T: 0.00"
                    - generic [ref=e576]:
                      - img [ref=e577]
                      - generic [ref=e581]: "L: 0.00"
                - listitem [ref=e582] [cursor=pointer]:
                  - generic [ref=e583]:
                    - generic [ref=e585]: L
                    - generic [ref=e586]:
                      - generic [ref=e588]: "#16"
                      - generic [ref=e589]: Leon
                  - generic [ref=e591]:
                    - generic [ref=e592]:
                      - img [ref=e593]
                      - generic [ref=e595]: 05:30 AM
                    - generic [ref=e596]:
                      - img [ref=e597]
                      - generic [ref=e599]: "Turn: 0.0"
                    - generic [ref=e600]:
                      - img [ref=e601]
                      - generic [ref=e606]: "T: 0.00"
                    - generic [ref=e607]:
                      - img [ref=e608]
                      - generic [ref=e612]: "L: 0.00"
                - listitem [ref=e613] [cursor=pointer]:
                  - generic [ref=e614]:
                    - generic [ref=e616]: C
                    - generic [ref=e617]:
                      - generic [ref=e619]: "#17"
                      - generic [ref=e620]: Charlotte
                  - generic [ref=e622]:
                    - generic [ref=e623]:
                      - img [ref=e624]
                      - generic [ref=e626]: 05:31 AM
                    - generic [ref=e627]:
                      - img [ref=e628]
                      - generic [ref=e630]: "Turn: 0.0"
                    - generic [ref=e631]:
                      - img [ref=e632]
                      - generic [ref=e637]: "T: 0.00"
                    - generic [ref=e638]:
                      - img [ref=e639]
                      - generic [ref=e643]: "L: 0.00"
                - listitem [ref=e644] [cursor=pointer]:
                  - generic [ref=e645]:
                    - generic [ref=e647]: C
                    - generic [ref=e648]:
                      - generic [ref=e650]: "#18"
                      - generic [ref=e651]: CC_Slip
                  - generic [ref=e653]:
                    - generic [ref=e654]:
                      - img [ref=e655]
                      - generic [ref=e657]: 05:32 AM
                    - generic [ref=e658]:
                      - img [ref=e659]
                      - generic [ref=e661]: "Turn: 0.0"
                    - generic [ref=e662]:
                      - img [ref=e663]
                      - generic [ref=e668]: "T: 0.00"
                    - generic [ref=e669]:
                      - img [ref=e670]
                      - generic [ref=e674]: "L: 0.00"
                - listitem [ref=e675] [cursor=pointer]:
                  - generic [ref=e676]:
                    - generic [ref=e678]: C
                    - generic [ref=e679]:
                      - generic [ref=e681]: "#19"
                      - generic [ref=e682]: CCSlipNoTip
                  - generic [ref=e684]:
                    - generic [ref=e685]:
                      - img [ref=e686]
                      - generic [ref=e688]: 05:32 AM
                    - generic [ref=e689]:
                      - img [ref=e690]
                      - generic [ref=e692]: "Turn: 0.0"
                    - generic [ref=e693]:
                      - img [ref=e694]
                      - generic [ref=e699]: "T: 0.00"
                    - generic [ref=e700]:
                      - img [ref=e701]
                      - generic [ref=e705]: "L: 0.00"
                - listitem [ref=e706] [cursor=pointer]:
                  - generic [ref=e707]:
                    - generic [ref=e709]: W
                    - generic [ref=e710]:
                      - generic [ref=e712]: "#20"
                      - generic [ref=e713]: WorkSlip
                  - generic [ref=e715]:
                    - generic [ref=e716]:
                      - img [ref=e717]
                      - generic [ref=e719]: 05:32 AM
                    - generic [ref=e720]:
                      - img [ref=e721]
                      - generic [ref=e723]: "Turn: 0.0"
                    - generic [ref=e724]:
                      - img [ref=e725]
                      - generic [ref=e730]: "T: 0.00"
                    - generic [ref=e731]:
                      - img [ref=e732]
                      - generic [ref=e736]: "L: 0.00"
                - listitem [ref=e737] [cursor=pointer]:
                  - generic [ref=e738]:
                    - generic [ref=e740]: W
                    - generic [ref=e741]:
                      - generic [ref=e743]: "#21"
                      - generic [ref=e744]: WorkSlipAdjustTip
                  - generic [ref=e746]:
                    - generic [ref=e747]:
                      - img [ref=e748]
                      - generic [ref=e750]: 05:32 AM
                    - generic [ref=e751]:
                      - img [ref=e752]
                      - generic [ref=e754]: "Turn: 0.0"
                    - generic [ref=e755]:
                      - img [ref=e756]
                      - generic [ref=e761]: "T: 0.00"
                    - generic [ref=e762]:
                      - img [ref=e763]
                      - generic [ref=e767]: "L: 0.00"
                - listitem [ref=e768] [cursor=pointer]:
                  - generic [ref=e769]:
                    - generic [ref=e771]: A
                    - generic [ref=e772]:
                      - generic [ref=e774]: "#22"
                      - generic [ref=e775]: Avery
                  - generic [ref=e777]:
                    - generic [ref=e778]:
                      - img [ref=e779]
                      - generic [ref=e781]: 07:00 AM
                    - generic [ref=e782]:
                      - img [ref=e783]
                      - generic [ref=e785]: "Turn: 0.0"
                    - generic [ref=e786]:
                      - img [ref=e787]
                      - generic [ref=e792]: "T: 0.00"
                    - generic [ref=e793]:
                      - img [ref=e794]
                      - generic [ref=e798]: "L: 0.00"
                - listitem [ref=e799] [cursor=pointer]:
                  - generic [ref=e800]:
                    - generic [ref=e802]: H
                    - generic [ref=e803]:
                      - generic [ref=e805]: "#23"
                      - generic [ref=e806]: Hailey
                  - generic [ref=e808]:
                    - generic [ref=e809]:
                      - img [ref=e810]
                      - generic [ref=e812]: 07:00 AM
                    - generic [ref=e813]:
                      - img [ref=e814]
                      - generic [ref=e816]: "Turn: 0.0"
                    - generic [ref=e817]:
                      - img [ref=e818]
                      - generic [ref=e823]: "T: 0.00"
                    - generic [ref=e824]:
                      - img [ref=e825]
                      - generic [ref=e829]: "L: 0.00"
                - listitem [ref=e830] [cursor=pointer]:
                  - generic [ref=e831]:
                    - generic [ref=e833]: B
                    - generic [ref=e834]:
                      - generic [ref=e836]: "#24"
                      - generic [ref=e837]: Brenna
                  - generic [ref=e839]:
                    - generic [ref=e840]:
                      - img [ref=e841]
                      - generic [ref=e843]: 07:00 AM
                    - generic [ref=e844]:
                      - img [ref=e845]
                      - generic [ref=e847]: "Turn: 0.0"
                    - generic [ref=e848]:
                      - img [ref=e849]
                      - generic [ref=e854]: "T: 0.00"
                    - generic [ref=e855]:
                      - img [ref=e856]
                      - generic [ref=e860]: "L: 0.00"
                - listitem [ref=e861] [cursor=pointer]:
                  - generic [ref=e862]:
                    - generic [ref=e864]: L
                    - generic [ref=e865]:
                      - generic [ref=e867]: "#25"
                      - generic [ref=e868]: Leah
                  - generic [ref=e870]:
                    - generic [ref=e871]:
                      - img [ref=e872]
                      - generic [ref=e874]: 07:00 AM
                    - generic [ref=e875]:
                      - img [ref=e876]
                      - generic [ref=e878]: "Turn: 0.0"
                    - generic [ref=e879]:
                      - img [ref=e880]
                      - generic [ref=e885]: "T: 0.00"
                    - generic [ref=e886]:
                      - img [ref=e887]
                      - generic [ref=e891]: "L: 0.00"
                - listitem [ref=e892] [cursor=pointer]:
                  - generic [ref=e893]:
                    - generic [ref=e895]: V
                    - generic [ref=e896]:
                      - generic [ref=e898]: "#26"
                      - generic [ref=e899]: Victoria
                  - generic [ref=e901]:
                    - generic [ref=e902]:
                      - img [ref=e903]
                      - generic [ref=e905]: 07:00 AM
                    - generic [ref=e906]:
                      - img [ref=e907]
                      - generic [ref=e909]: "Turn: 0.0"
                    - generic [ref=e910]:
                      - img [ref=e911]
                      - generic [ref=e916]: "T: 0.00"
                    - generic [ref=e917]:
                      - img [ref=e918]
                      - generic [ref=e922]: "L: 0.00"
                - listitem [ref=e923] [cursor=pointer]:
                  - generic [ref=e924]:
                    - generic [ref=e926]: S
                    - generic [ref=e927]:
                      - generic [ref=e929]: "#27"
                      - generic [ref=e930]: Sandy
                  - generic [ref=e932]:
                    - generic [ref=e933]:
                      - img [ref=e934]
                      - generic [ref=e936]: 07:00 AM
                    - generic [ref=e937]:
                      - img [ref=e938]
                      - generic [ref=e940]: "Turn: 0.0"
                    - generic [ref=e941]:
                      - img [ref=e942]
                      - generic [ref=e947]: "T: 0.00"
                    - generic [ref=e948]:
                      - img [ref=e949]
                      - generic [ref=e953]: "L: 0.00"
                - listitem [ref=e954] [cursor=pointer]:
                  - generic [ref=e955]:
                    - generic [ref=e957]: T
                    - generic [ref=e958]:
                      - generic [ref=e960]: "#28"
                      - generic [ref=e961]: Tom
                  - generic [ref=e963]:
                    - generic [ref=e964]:
                      - img [ref=e965]
                      - generic [ref=e967]: 07:00 AM
                    - generic [ref=e968]:
                      - img [ref=e969]
                      - generic [ref=e971]: "Turn: 0.0"
                    - generic [ref=e972]:
                      - img [ref=e973]
                      - generic [ref=e978]: "T: 0.00"
                    - generic [ref=e979]:
                      - img [ref=e980]
                      - generic [ref=e984]: "L: 0.00"
                - listitem [ref=e985] [cursor=pointer]:
                  - generic [ref=e986]:
                    - generic [ref=e988]: S
                    - generic [ref=e989]:
                      - generic [ref=e991]: "#29"
                      - generic [ref=e992]: Sarah
                  - generic [ref=e994]:
                    - generic [ref=e995]:
                      - img [ref=e996]
                      - generic [ref=e998]: 07:00 AM
                    - generic [ref=e999]:
                      - img [ref=e1000]
                      - generic [ref=e1002]: "Turn: 0.0"
                    - generic [ref=e1003]:
                      - img [ref=e1004]
                      - generic [ref=e1009]: "T: 0.00"
                    - generic [ref=e1010]:
                      - img [ref=e1011]
                      - generic [ref=e1015]: "L: 0.00"
                - listitem [ref=e1016] [cursor=pointer]:
                  - generic [ref=e1017]:
                    - generic [ref=e1019]: A
                    - generic [ref=e1020]:
                      - generic [ref=e1022]: "#30"
                      - generic [ref=e1023]: Amelia
                  - generic [ref=e1025]:
                    - generic [ref=e1026]:
                      - img [ref=e1027]
                      - generic [ref=e1029]: 07:00 AM
                    - generic [ref=e1030]:
                      - img [ref=e1031]
                      - generic [ref=e1033]: "Turn: 0.0"
                    - generic [ref=e1034]:
                      - img [ref=e1035]
                      - generic [ref=e1040]: "T: 0.00"
                    - generic [ref=e1041]:
                      - img [ref=e1042]
                      - generic [ref=e1046]: "L: 0.00"
                - listitem [ref=e1047] [cursor=pointer]:
                  - generic [ref=e1048]:
                    - generic [ref=e1050]: B
                    - generic [ref=e1051]:
                      - generic [ref=e1053]: "#31"
                      - generic [ref=e1054]: Bella
                  - generic [ref=e1056]:
                    - generic [ref=e1057]:
                      - img [ref=e1058]
                      - generic [ref=e1060]: 12:00 AM
                    - generic [ref=e1061]:
                      - img [ref=e1062]
                      - generic [ref=e1064]: "Turn: 0.0"
                    - generic [ref=e1065]:
                      - img [ref=e1066]
                      - generic [ref=e1071]: "T: 3.00"
                    - generic [ref=e1072]:
                      - img [ref=e1073]
                      - generic [ref=e1077]: "L: 3.00"
                - listitem [ref=e1078] [cursor=pointer]:
                  - generic [ref=e1079]:
                    - generic [ref=e1081]: J
                    - generic [ref=e1082]:
                      - generic [ref=e1084]: "#32"
                      - generic [ref=e1085]: Jasmine
                  - generic [ref=e1087]:
                    - generic [ref=e1088]:
                      - img [ref=e1089]
                      - generic [ref=e1091]: 05:29 AM
                    - generic [ref=e1092]:
                      - img [ref=e1093]
                      - generic [ref=e1095]: "Turn: 0.0"
                    - generic [ref=e1096]:
                      - img [ref=e1097]
                      - generic [ref=e1102]: "T: 5.40"
                    - generic [ref=e1103]:
                      - img [ref=e1104]
                      - generic [ref=e1108]: "L: 5.40"
                - listitem [ref=e1109] [cursor=pointer]:
                  - generic [ref=e1110]:
                    - generic [ref=e1112]: R
                    - generic [ref=e1113]:
                      - generic [ref=e1115]: "#33"
                      - generic [ref=e1116]: Ruby
                  - generic [ref=e1118]:
                    - generic [ref=e1119]:
                      - img [ref=e1120]
                      - generic [ref=e1122]: 07:00 AM
                    - generic [ref=e1123]:
                      - img [ref=e1124]
                      - generic [ref=e1126]: "Turn: 0.0"
                    - generic [ref=e1127]:
                      - img [ref=e1128]
                      - generic [ref=e1133]: "T: 5.40"
                    - generic [ref=e1134]:
                      - img [ref=e1135]
                      - generic [ref=e1139]: "L: 5.40"
                - listitem [ref=e1140] [cursor=pointer]:
                  - generic [ref=e1141]:
                    - generic [ref=e1143]: D
                    - generic [ref=e1144]:
                      - generic [ref=e1146]: "#34"
                      - generic [ref=e1147]: Dylan
                  - generic [ref=e1149]:
                    - generic [ref=e1150]:
                      - img [ref=e1151]
                      - generic [ref=e1153]: 05:24 AM
                    - generic [ref=e1154]:
                      - img [ref=e1155]
                      - generic [ref=e1157]: "Turn: 0.0"
                    - generic [ref=e1158]:
                      - img [ref=e1159]
                      - generic [ref=e1164]: "T: 6.00"
                    - generic [ref=e1165]:
                      - img [ref=e1166]
                      - generic [ref=e1170]: "L: 6.00"
                - listitem [ref=e1171] [cursor=pointer]:
                  - generic [ref=e1172]:
                    - img "item service Owner" [ref=e1175]
                    - generic [ref=e1176]:
                      - generic [ref=e1178]: "#35"
                      - generic [ref=e1179]: Owner
                  - generic [ref=e1181]:
                    - generic [ref=e1182]:
                      - img [ref=e1183]
                      - generic [ref=e1185]: 05:24 AM
                    - generic [ref=e1186]:
                      - img [ref=e1187]
                      - generic [ref=e1189]: "Turn: 0.0"
                    - generic [ref=e1190]:
                      - img [ref=e1191]
                      - generic [ref=e1196]: "T: 6.00"
                    - generic [ref=e1197]:
                      - img [ref=e1198]
                      - generic [ref=e1202]: "L: 6.00"
                - listitem [ref=e1203] [cursor=pointer]:
                  - generic [ref=e1204]:
                    - generic [ref=e1206]: T
                    - generic [ref=e1207]:
                      - generic [ref=e1209]: "#36"
                      - generic [ref=e1210]: Tim
                  - generic [ref=e1212]:
                    - generic [ref=e1213]:
                      - img [ref=e1214]
                      - generic [ref=e1216]: 05:24 AM
                    - generic [ref=e1217]:
                      - img [ref=e1218]
                      - generic [ref=e1220]: "Turn: 0.0"
                    - generic [ref=e1221]:
                      - img [ref=e1222]
                      - generic [ref=e1227]: "T: 6.00"
                    - generic [ref=e1228]:
                      - img [ref=e1229]
                      - generic [ref=e1233]: "L: 6.00"
                - listitem [ref=e1234] [cursor=pointer]:
                  - generic [ref=e1235]:
                    - generic [ref=e1237]: K
                    - generic [ref=e1238]:
                      - generic [ref=e1240]: "#37"
                      - generic [ref=e1241]: Keelin
                  - generic [ref=e1243]:
                    - generic [ref=e1244]:
                      - img [ref=e1245]
                      - generic [ref=e1247]: 05:30 AM
                    - generic [ref=e1248]:
                      - img [ref=e1249]
                      - generic [ref=e1251]: "Turn: 0.0"
                    - generic [ref=e1252]:
                      - img [ref=e1253]
                      - generic [ref=e1258]: "T: 6.00"
                    - generic [ref=e1259]:
                      - img [ref=e1260]
                      - generic [ref=e1264]: "L: 6.00"
                - listitem [ref=e1265] [cursor=pointer]:
                  - generic [ref=e1266]:
                    - generic [ref=e1268]: H
                    - generic [ref=e1269]:
                      - generic [ref=e1271]: "#38"
                      - generic [ref=e1272]: Hanna
                  - generic [ref=e1274]:
                    - generic [ref=e1275]:
                      - img [ref=e1276]
                      - generic [ref=e1278]: 07:00 AM
                    - generic [ref=e1279]:
                      - img [ref=e1280]
                      - generic [ref=e1282]: "Turn: 0.0"
                    - generic [ref=e1283]:
                      - img [ref=e1284]
                      - generic [ref=e1289]: "T: 6.00"
                    - generic [ref=e1290]:
                      - img [ref=e1291]
                      - generic [ref=e1295]: "L: 6.00"
                - listitem [ref=e1296] [cursor=pointer]:
                  - generic [ref=e1297]:
                    - generic [ref=e1299]: L
                    - generic [ref=e1300]:
                      - generic [ref=e1302]: "#39"
                      - generic [ref=e1303]: Laura
                  - generic [ref=e1305]:
                    - generic [ref=e1306]:
                      - img [ref=e1307]
                      - generic [ref=e1309]: 07:00 AM
                    - generic [ref=e1310]:
                      - img [ref=e1311]
                      - generic [ref=e1313]: "Turn: 0.0"
                    - generic [ref=e1314]:
                      - img [ref=e1315]
                      - generic [ref=e1320]: "T: 6.00"
                    - generic [ref=e1321]:
                      - img [ref=e1322]
                      - generic [ref=e1326]: "L: 6.00"
                - listitem [ref=e1327] [cursor=pointer]:
                  - generic [ref=e1328]:
                    - generic [ref=e1330]: E
                    - generic [ref=e1331]:
                      - generic [ref=e1333]: "#40"
                      - generic [ref=e1334]: Eira
                  - generic [ref=e1336]:
                    - generic [ref=e1337]:
                      - img [ref=e1338]
                      - generic [ref=e1340]: 07:00 AM
                    - generic [ref=e1341]:
                      - img [ref=e1342]
                      - generic [ref=e1344]: "Turn: 0.0"
                    - generic [ref=e1345]:
                      - img [ref=e1346]
                      - generic [ref=e1351]: "T: 6.00"
                    - generic [ref=e1352]:
                      - img [ref=e1353]
                      - generic [ref=e1357]: "L: 6.00"
                - listitem [ref=e1358] [cursor=pointer]:
                  - generic [ref=e1359]:
                    - generic [ref=e1361]: E
                    - generic [ref=e1362]:
                      - generic [ref=e1364]: "#41"
                      - generic [ref=e1365]: Emily
                  - generic [ref=e1367]:
                    - generic [ref=e1368]:
                      - img [ref=e1369]
                      - generic [ref=e1371]: 07:00 AM
                    - generic [ref=e1372]:
                      - img [ref=e1373]
                      - generic [ref=e1375]: "Turn: 0.0"
                    - generic [ref=e1376]:
                      - img [ref=e1377]
                      - generic [ref=e1382]: "T: 6.00"
                    - generic [ref=e1383]:
                      - img [ref=e1384]
                      - generic [ref=e1388]: "L: 6.00"
                - listitem [ref=e1389] [cursor=pointer]:
                  - generic [ref=e1390]:
                    - img "item service Emma" [ref=e1393]
                    - generic [ref=e1394]:
                      - generic [ref=e1396]: "#42"
                      - generic [ref=e1397]: Emma
                  - generic [ref=e1399]:
                    - generic [ref=e1400]:
                      - img [ref=e1401]
                      - generic [ref=e1403]: 07:00 AM
                    - generic [ref=e1404]:
                      - img [ref=e1405]
                      - generic [ref=e1407]: "Turn: 0.0"
                    - generic [ref=e1408]:
                      - img [ref=e1409]
                      - generic [ref=e1414]: "T: 6.00"
                    - generic [ref=e1415]:
                      - img [ref=e1416]
                      - generic [ref=e1420]: "L: 6.00"
                - listitem [ref=e1421] [cursor=pointer]:
                  - generic [ref=e1422]:
                    - generic [ref=e1424]: A
                    - generic [ref=e1425]:
                      - generic [ref=e1427]: "#43"
                      - generic [ref=e1428]: Ava
                  - generic [ref=e1430]:
                    - generic [ref=e1431]:
                      - img [ref=e1432]
                      - generic [ref=e1434]: 05:25 AM
                    - generic [ref=e1435]:
                      - img [ref=e1436]
                      - generic [ref=e1438]: "Turn: 0.0"
                    - generic [ref=e1439]:
                      - img [ref=e1440]
                      - generic [ref=e1445]: "T: 8.00"
                    - generic [ref=e1446]:
                      - img [ref=e1447]
                      - generic [ref=e1451]: "L: 8.00"
                - listitem [ref=e1452] [cursor=pointer]:
                  - generic [ref=e1453]:
                    - generic [ref=e1455]: D
                    - generic [ref=e1456]:
                      - generic [ref=e1458]: "#44"
                      - generic [ref=e1459]: Daniel
                  - generic [ref=e1461]:
                    - generic [ref=e1462]:
                      - img [ref=e1463]
                      - generic [ref=e1465]: 05:29 AM
                    - generic [ref=e1466]:
                      - img [ref=e1467]
                      - generic [ref=e1469]: "Turn: 0.0"
                    - generic [ref=e1470]:
                      - img [ref=e1471]
                      - generic [ref=e1476]: "T: 8.00"
                    - generic [ref=e1477]:
                      - img [ref=e1478]
                      - generic [ref=e1482]: "L: 8.00"
                - listitem [ref=e1483] [cursor=pointer]:
                  - generic [ref=e1484]:
                    - generic [ref=e1486]: F
                    - generic [ref=e1487]:
                      - generic [ref=e1489]: "#45"
                      - generic [ref=e1490]: Fiona
                  - generic [ref=e1492]:
                    - generic [ref=e1493]:
                      - img [ref=e1494]
                      - generic [ref=e1496]: 05:29 AM
                    - generic [ref=e1497]:
                      - img [ref=e1498]
                      - generic [ref=e1500]: "Turn: 0.0"
                    - generic [ref=e1501]:
                      - img [ref=e1502]
                      - generic [ref=e1507]: "T: 8.00"
                    - generic [ref=e1508]:
                      - img [ref=e1509]
                      - generic [ref=e1513]: "L: 8.00"
                - listitem [ref=e1514] [cursor=pointer]:
                  - generic [ref=e1515]:
                    - generic [ref=e1517]: S
                    - generic [ref=e1518]:
                      - generic [ref=e1520]: "#46"
                      - generic [ref=e1521]: Savannah
                  - generic [ref=e1523]:
                    - generic [ref=e1524]:
                      - img [ref=e1525]
                      - generic [ref=e1527]: 07:00 AM
                    - generic [ref=e1528]:
                      - img [ref=e1529]
                      - generic [ref=e1531]: "Turn: 0.0"
                    - generic [ref=e1532]:
                      - img [ref=e1533]
                      - generic [ref=e1538]: "T: 8.00"
                    - generic [ref=e1539]:
                      - img [ref=e1540]
                      - generic [ref=e1544]: "L: 8.00"
                - listitem [ref=e1545] [cursor=pointer]:
                  - generic [ref=e1546]:
                    - generic [ref=e1548]: C
                    - generic [ref=e1549]:
                      - generic [ref=e1551]: "#47"
                      - generic [ref=e1552]: Claire
                  - generic [ref=e1554]:
                    - generic [ref=e1555]:
                      - img [ref=e1556]
                      - generic [ref=e1558]: 07:00 AM
                    - generic [ref=e1559]:
                      - img [ref=e1560]
                      - generic [ref=e1562]: "Turn: 0.0"
                    - generic [ref=e1563]:
                      - img [ref=e1564]
                      - generic [ref=e1569]: "T: 8.00"
                    - generic [ref=e1570]:
                      - img [ref=e1571]
                      - generic [ref=e1575]: "L: 8.00"
                - listitem [ref=e1576] [cursor=pointer]:
                  - generic [ref=e1577]:
                    - generic [ref=e1579]: T
                    - generic [ref=e1580]:
                      - generic [ref=e1582]: "#48"
                      - generic [ref=e1583]: Tina
                  - generic [ref=e1585]:
                    - generic [ref=e1586]:
                      - img [ref=e1587]
                      - generic [ref=e1589]: 07:00 AM
                    - generic [ref=e1590]:
                      - img [ref=e1591]
                      - generic [ref=e1593]: "Turn: 0.0"
                    - generic [ref=e1594]:
                      - img [ref=e1595]
                      - generic [ref=e1600]: "T: 8.00"
                    - generic [ref=e1601]:
                      - img [ref=e1602]
                      - generic [ref=e1606]: "L: 8.00"
                - listitem [ref=e1607] [cursor=pointer]:
                  - generic [ref=e1608]:
                    - generic [ref=e1610]: M
                    - generic [ref=e1611]:
                      - generic [ref=e1613]: "#49"
                      - generic [ref=e1614]: Maya
                  - generic [ref=e1616]:
                    - generic [ref=e1617]:
                      - img [ref=e1618]
                      - generic [ref=e1620]: 07:00 AM
                    - generic [ref=e1621]:
                      - img [ref=e1622]
                      - generic [ref=e1624]: "Turn: 0.0"
                    - generic [ref=e1625]:
                      - img [ref=e1626]
                      - generic [ref=e1631]: "T: 8.00"
                    - generic [ref=e1632]:
                      - img [ref=e1633]
                      - generic [ref=e1637]: "L: 8.00"
                - listitem [ref=e1638] [cursor=pointer]:
                  - generic [ref=e1639]:
                    - generic [ref=e1641]: B
                    - generic [ref=e1642]:
                      - generic [ref=e1644]: "#50"
                      - generic [ref=e1645]: Brian
                  - generic [ref=e1647]:
                    - generic [ref=e1648]:
                      - img [ref=e1649]
                      - generic [ref=e1651]: 07:00 AM
                    - generic [ref=e1652]:
                      - img [ref=e1653]
                      - generic [ref=e1655]: "Turn: 0.0"
                    - generic [ref=e1656]:
                      - img [ref=e1657]
                      - generic [ref=e1662]: "T: 8.00"
                    - generic [ref=e1663]:
                      - img [ref=e1664]
                      - generic [ref=e1668]: "L: 8.00"
                - listitem [ref=e1669] [cursor=pointer]:
                  - generic [ref=e1670]:
                    - generic [ref=e1672]: K
                    - generic [ref=e1673]:
                      - generic [ref=e1675]: "#51"
                      - generic [ref=e1676]: Kayla
                  - generic [ref=e1678]:
                    - generic [ref=e1679]:
                      - img [ref=e1680]
                      - generic [ref=e1682]: 05:28 AM
                    - generic [ref=e1683]:
                      - img [ref=e1684]
                      - generic [ref=e1686]: "Turn: 0.0"
                    - generic [ref=e1687]:
                      - img [ref=e1688]
                      - generic [ref=e1693]: "T: 10.00"
                    - generic [ref=e1694]:
                      - img [ref=e1695]
                      - generic [ref=e1699]: "L: 10.00"
                - listitem [ref=e1700] [cursor=pointer]:
                  - generic [ref=e1701]:
                    - generic [ref=e1703]: C
                    - generic [ref=e1704]:
                      - generic [ref=e1706]: "#52"
                      - generic [ref=e1707]: Chloe
                  - generic [ref=e1709]:
                    - generic [ref=e1710]:
                      - img [ref=e1711]
                      - generic [ref=e1713]: 05:27 AM
                    - generic [ref=e1714]:
                      - img [ref=e1715]
                      - generic [ref=e1717]: "Turn: 0.0"
                    - generic [ref=e1718]:
                      - img [ref=e1719]
                      - generic [ref=e1724]: "T: 11.50"
                    - generic [ref=e1725]:
                      - img [ref=e1726]
                      - generic [ref=e1730]: "L: 11.50"
                - listitem [ref=e1731] [cursor=pointer]:
                  - generic [ref=e1732]:
                    - generic [ref=e1734]: A
                    - generic [ref=e1735]:
                      - generic [ref=e1737]: "#53"
                      - generic [ref=e1738]: Angie
                  - generic [ref=e1740]:
                    - generic [ref=e1741]:
                      - img [ref=e1742]
                      - generic [ref=e1744]: 05:28 AM
                    - generic [ref=e1745]:
                      - img [ref=e1746]
                      - generic [ref=e1748]: "Turn: 0.0"
                    - generic [ref=e1749]:
                      - img [ref=e1750]
                      - generic [ref=e1755]: "T: 12.00"
                    - generic [ref=e1756]:
                      - img [ref=e1757]
                      - generic [ref=e1761]: "L: 12.00"
                - listitem [ref=e1762] [cursor=pointer]:
                  - generic [ref=e1763]:
                    - generic [ref=e1765]: t
                    - generic [ref=e1766]:
                      - generic [ref=e1768]: "#54"
                      - generic [ref=e1769]: thanh
                  - generic [ref=e1771]:
                    - generic [ref=e1772]:
                      - img [ref=e1773]
                      - generic [ref=e1775]: 05:28 AM
                    - generic [ref=e1776]:
                      - img [ref=e1777]
                      - generic [ref=e1779]: "Turn: 0.0"
                    - generic [ref=e1780]:
                      - img [ref=e1781]
                      - generic [ref=e1786]: "T: 12.00"
                    - generic [ref=e1787]:
                      - img [ref=e1788]
                      - generic [ref=e1792]: "L: 12.00"
                - listitem [ref=e1793] [cursor=pointer]:
                  - generic [ref=e1794]:
                    - generic [ref=e1796]: I
                    - generic [ref=e1797]:
                      - generic [ref=e1799]: "#55"
                      - generic [ref=e1800]: Iris
                  - generic [ref=e1802]:
                    - generic [ref=e1803]:
                      - img [ref=e1804]
                      - generic [ref=e1806]: 05:25 AM
                    - generic [ref=e1807]:
                      - img [ref=e1808]
                      - generic [ref=e1810]: "Turn: 0.0"
                    - generic [ref=e1811]:
                      - img [ref=e1812]
                      - generic [ref=e1817]: "T: 16.00"
                    - generic [ref=e1818]:
                      - img [ref=e1819]
                      - generic [ref=e1823]: "L: 16.00"
                - listitem [ref=e1824] [cursor=pointer]:
                  - generic [ref=e1825]:
                    - generic [ref=e1827]: L
                    - generic [ref=e1828]:
                      - generic [ref=e1830]: "#56"
                      - generic [ref=e1831]: Luna
                  - generic [ref=e1833]:
                    - generic [ref=e1834]:
                      - img [ref=e1835]
                      - generic [ref=e1837]: 05:25 AM
                    - generic [ref=e1838]:
                      - img [ref=e1839]
                      - generic [ref=e1841]: "Turn: 0.0"
                    - generic [ref=e1842]:
                      - img [ref=e1843]
                      - generic [ref=e1848]: "T: 16.00"
                    - generic [ref=e1849]:
                      - img [ref=e1850]
                      - generic [ref=e1854]: "L: 16.00"
                - listitem [ref=e1855] [cursor=pointer]:
                  - generic [ref=e1856]:
                    - generic [ref=e1858]: J
                    - generic [ref=e1859]:
                      - generic [ref=e1861]: "#57"
                      - generic [ref=e1862]: Jack
                  - generic [ref=e1864]:
                    - generic [ref=e1865]:
                      - img [ref=e1866]
                      - generic [ref=e1868]: 07:00 AM
                    - generic [ref=e1869]:
                      - img [ref=e1870]
                      - generic [ref=e1872]: "Turn: 0.0"
                    - generic [ref=e1873]:
                      - img [ref=e1874]
                      - generic [ref=e1879]: "T: 16.00"
                    - generic [ref=e1880]:
                      - img [ref=e1881]
                      - generic [ref=e1885]: "L: 16.00"
                - listitem [ref=e1886] [cursor=pointer]:
                  - generic [ref=e1887]:
                    - generic [ref=e1889]: W
                    - generic [ref=e1890]:
                      - generic [ref=e1892]: "#58"
                      - generic [ref=e1893]: Willow
                  - generic [ref=e1895]:
                    - generic [ref=e1896]:
                      - img [ref=e1897]
                      - generic [ref=e1899]: 05:31 AM
                    - generic [ref=e1900]:
                      - img [ref=e1901]
                      - generic [ref=e1903]: "Turn: 0.0"
                    - generic [ref=e1904]:
                      - img [ref=e1905]
                      - generic [ref=e1910]: "T: 17.50"
                    - generic [ref=e1911]:
                      - img [ref=e1912]
                      - generic [ref=e1916]: "L: 17.50"
                - listitem [ref=e1917] [cursor=pointer]:
                  - generic [ref=e1918]:
                    - generic [ref=e1920]: C
                    - generic [ref=e1921]:
                      - generic [ref=e1923]: "#59"
                      - generic [ref=e1924]: Camellia
                  - generic [ref=e1926]:
                    - generic [ref=e1927]:
                      - img [ref=e1928]
                      - generic [ref=e1930]: 05:31 AM
                    - generic [ref=e1931]:
                      - img [ref=e1932]
                      - generic [ref=e1934]: "Turn: 0.0"
                    - generic [ref=e1935]:
                      - img [ref=e1936]
                      - generic [ref=e1941]: "T: 17.50"
                    - generic [ref=e1942]:
                      - img [ref=e1943]
                      - generic [ref=e1947]: "L: 17.50"
                - listitem [ref=e1948] [cursor=pointer]:
                  - generic [ref=e1949]:
                    - generic [ref=e1951]: S
                    - generic [ref=e1952]:
                      - generic [ref=e1954]: "#60"
                      - generic [ref=e1955]: Sam
                  - generic [ref=e1957]:
                    - generic [ref=e1958]:
                      - img [ref=e1959]
                      - generic [ref=e1961]: 07:00 AM
                    - generic [ref=e1962]:
                      - img [ref=e1963]
                      - generic [ref=e1965]: "Turn: 0.0"
                    - generic [ref=e1966]:
                      - img [ref=e1967]
                      - generic [ref=e1972]: "T: 18.00"
                    - generic [ref=e1973]:
                      - img [ref=e1974]
                      - generic [ref=e1978]: "L: 18.00"
                - listitem [ref=e1979] [cursor=pointer]:
                  - generic [ref=e1980]:
                    - generic [ref=e1982]: A
                    - generic [ref=e1983]:
                      - generic [ref=e1985]: "#61"
                      - generic [ref=e1986]: Addison
                  - generic [ref=e1988]:
                    - generic [ref=e1989]:
                      - img [ref=e1990]
                      - generic [ref=e1992]: 12:00 AM
                    - generic [ref=e1993]:
                      - img [ref=e1994]
                      - generic [ref=e1996]: "Turn: 1.0"
                    - generic [ref=e1997]:
                      - img [ref=e1998]
                      - generic [ref=e2003]: "T: 20.00"
                    - generic [ref=e2004]:
                      - img [ref=e2005]
                      - generic [ref=e2009]: "L: 37.00"
                - listitem [ref=e2010] [cursor=pointer]:
                  - generic [ref=e2011]:
                    - generic [ref=e2013]: H
                    - generic [ref=e2014]:
                      - generic [ref=e2016]: "#62"
                      - generic [ref=e2017]: Harry
                  - generic [ref=e2019]:
                    - generic [ref=e2020]:
                      - img [ref=e2021]
                      - generic [ref=e2023]: 07:00 AM
                    - generic [ref=e2024]:
                      - img [ref=e2025]
                      - generic [ref=e2027]: "Turn: 1.0"
                    - generic [ref=e2028]:
                      - img [ref=e2029]
                      - generic [ref=e2034]: "T: 20.00"
                    - generic [ref=e2035]:
                      - img [ref=e2036]
                      - generic [ref=e2040]: "L: 20.00"
                - listitem [ref=e2041] [cursor=pointer]:
                  - generic [ref=e2042]:
                    - generic [ref=e2044]: A
                    - generic [ref=e2045]:
                      - generic [ref=e2047]: "#63"
                      - generic [ref=e2048]: Almira
                  - generic [ref=e2050]:
                    - generic [ref=e2051]:
                      - img [ref=e2052]
                      - generic [ref=e2054]: 07:00 AM
                    - generic [ref=e2055]:
                      - img [ref=e2056]
                      - generic [ref=e2058]: "Turn: 1.0"
                    - generic [ref=e2059]:
                      - img [ref=e2060]
                      - generic [ref=e2065]: "T: 22.00"
                    - generic [ref=e2066]:
                      - img [ref=e2067]
                      - generic [ref=e2071]: "L: 22.00"
                - listitem [ref=e2072] [cursor=pointer]:
                  - generic [ref=e2073]:
                    - generic [ref=e2075]: S
                    - generic [ref=e2076]:
                      - generic [ref=e2078]: "#64"
                      - generic [ref=e2079]: Samantha
                  - generic [ref=e2081]:
                    - generic [ref=e2082]:
                      - img [ref=e2083]
                      - generic [ref=e2085]: 05:28 AM
                    - generic [ref=e2086]:
                      - img [ref=e2087]
                      - generic [ref=e2089]: "Turn: 1.0"
                    - generic [ref=e2090]:
                      - img [ref=e2091]
                      - generic [ref=e2096]: "T: 23.50"
                    - generic [ref=e2097]:
                      - img [ref=e2098]
                      - generic [ref=e2102]: "L: 23.50"
                - listitem [ref=e2103] [cursor=pointer]:
                  - generic [ref=e2104]:
                    - generic [ref=e2106]: J
                    - generic [ref=e2107]:
                      - generic [ref=e2109]: "#65"
                      - generic [ref=e2110]: Julia
                  - generic [ref=e2112]:
                    - generic [ref=e2113]:
                      - img [ref=e2114]
                      - generic [ref=e2116]: 05:29 AM
                    - generic [ref=e2117]:
                      - img [ref=e2118]
                      - generic [ref=e2120]: "Turn: 1.0"
                    - generic [ref=e2121]:
                      - img [ref=e2122]
                      - generic [ref=e2127]: "T: 23.50"
                    - generic [ref=e2128]:
                      - img [ref=e2129]
                      - generic [ref=e2133]: "L: 23.50"
                - listitem [ref=e2134] [cursor=pointer]:
                  - generic [ref=e2135]:
                    - generic [ref=e2137]: A
                    - generic [ref=e2138]:
                      - generic [ref=e2140]: "#66"
                      - generic [ref=e2141]: Alexis
                  - generic [ref=e2143]:
                    - generic [ref=e2144]:
                      - img [ref=e2145]
                      - generic [ref=e2147]: 05:30 AM
                    - generic [ref=e2148]:
                      - img [ref=e2149]
                      - generic [ref=e2151]: "Turn: 1.0"
                    - generic [ref=e2152]:
                      - img [ref=e2153]
                      - generic [ref=e2158]: "T: 25.70"
                    - generic [ref=e2159]:
                      - img [ref=e2160]
                      - generic [ref=e2164]: "L: 25.70"
                - listitem [ref=e2165] [cursor=pointer]:
                  - generic [ref=e2166]:
                    - generic [ref=e2168]: M
                    - generic [ref=e2169]:
                      - generic [ref=e2171]: "#67"
                      - generic [ref=e2172]: Mackenzie
                  - generic [ref=e2174]:
                    - generic [ref=e2175]:
                      - img [ref=e2176]
                      - generic [ref=e2178]: 05:25 AM
                    - generic [ref=e2179]:
                      - img [ref=e2180]
                      - generic [ref=e2182]: "Turn: 1.0"
                    - generic [ref=e2183]:
                      - img [ref=e2184]
                      - generic [ref=e2189]: "T: 26.70"
                    - generic [ref=e2190]:
                      - img [ref=e2191]
                      - generic [ref=e2195]: "L: 26.70"
                - listitem [ref=e2196] [cursor=pointer]:
                  - generic [ref=e2197]:
                    - generic [ref=e2199]: "N"
                    - generic [ref=e2200]:
                      - generic [ref=e2202]: "#68"
                      - generic [ref=e2203]: Natalie
                  - generic [ref=e2205]:
                    - generic [ref=e2206]:
                      - img [ref=e2207]
                      - generic [ref=e2209]: 05:24 AM
                    - generic [ref=e2210]:
                      - img [ref=e2211]
                      - generic [ref=e2213]: "Turn: 1.0"
                    - generic [ref=e2214]:
                      - img [ref=e2215]
                      - generic [ref=e2220]: "T: 29.00"
                    - generic [ref=e2221]:
                      - img [ref=e2222]
                      - generic [ref=e2226]: "L: 29.00"
                - listitem [ref=e2227] [cursor=pointer]:
                  - generic [ref=e2228]:
                    - generic [ref=e2230]: E
                    - generic [ref=e2231]:
                      - generic [ref=e2233]: "#69"
                      - generic [ref=e2234]: Ethan
                  - generic [ref=e2236]:
                    - generic [ref=e2237]:
                      - img [ref=e2238]
                      - generic [ref=e2240]: 07:00 AM
                    - generic [ref=e2241]:
                      - img [ref=e2242]
                      - generic [ref=e2244]: "Turn: 1.0"
                    - generic [ref=e2245]:
                      - img [ref=e2246]
                      - generic [ref=e2251]: "T: 29.00"
                    - generic [ref=e2252]:
                      - img [ref=e2253]
                      - generic [ref=e2257]: "L: 29.00"
                - listitem [ref=e2258] [cursor=pointer]:
                  - generic [ref=e2259]:
                    - generic [ref=e2261]: S
                    - generic [ref=e2262]:
                      - generic [ref=e2264]: "#70"
                      - generic [ref=e2265]: Sophia
                  - generic [ref=e2267]:
                    - generic [ref=e2268]:
                      - img [ref=e2269]
                      - generic [ref=e2271]: 07:00 AM
                    - generic [ref=e2272]:
                      - img [ref=e2273]
                      - generic [ref=e2275]: "Turn: 1.0"
                    - generic [ref=e2276]:
                      - img [ref=e2277]
                      - generic [ref=e2282]: "T: 29.00"
                    - generic [ref=e2283]:
                      - img [ref=e2284]
                      - generic [ref=e2288]: "L: 29.00"
                - listitem [ref=e2289] [cursor=pointer]:
                  - generic [ref=e2290]:
                    - generic [ref=e2292]: G
                    - generic [ref=e2293]:
                      - generic [ref=e2295]: "#71"
                      - generic [ref=e2296]: Gabriella
                  - generic [ref=e2298]:
                    - generic [ref=e2299]:
                      - img [ref=e2300]
                      - generic [ref=e2302]: 07:00 AM
                    - generic [ref=e2303]:
                      - img [ref=e2304]
                      - generic [ref=e2306]: "Turn: 1.0"
                    - generic [ref=e2307]:
                      - img [ref=e2308]
                      - generic [ref=e2313]: "T: 29.25"
                    - generic [ref=e2314]:
                      - img [ref=e2315]
                      - generic [ref=e2319]: "L: 29.25"
                - listitem [ref=e2320] [cursor=pointer]:
                  - generic [ref=e2321]:
                    - generic [ref=e2323]: L
                    - generic [ref=e2324]:
                      - generic [ref=e2326]: "#72"
                      - generic [ref=e2327]: Lisa
                  - generic [ref=e2329]:
                    - generic [ref=e2330]:
                      - img [ref=e2331]
                      - generic [ref=e2333]: 07:00 AM
                    - generic [ref=e2334]:
                      - img [ref=e2335]
                      - generic [ref=e2337]: "Turn: 1.0"
                    - generic [ref=e2338]:
                      - img [ref=e2339]
                      - generic [ref=e2344]: "T: 30.00"
                    - generic [ref=e2345]:
                      - img [ref=e2346]
                      - generic [ref=e2350]: "L: 30.00"
                - listitem [ref=e2351] [cursor=pointer]:
                  - generic [ref=e2352]:
                    - generic [ref=e2354]: B
                    - generic [ref=e2355]:
                      - generic [ref=e2357]: "#73"
                      - generic [ref=e2358]: Brielle
                  - generic [ref=e2360]:
                    - generic [ref=e2361]:
                      - img [ref=e2362]
                      - generic [ref=e2364]: 05:31 AM
                    - generic [ref=e2365]:
                      - img [ref=e2366]
                      - generic [ref=e2368]: "Turn: 1.0"
                    - generic [ref=e2369]:
                      - img [ref=e2370]
                      - generic [ref=e2375]: "T: 33.40"
                    - generic [ref=e2376]:
                      - img [ref=e2377]
                      - generic [ref=e2381]: "L: 33.40"
                - listitem [ref=e2382] [cursor=pointer]:
                  - generic [ref=e2383]:
                    - generic [ref=e2385]: O
                    - generic [ref=e2386]:
                      - generic [ref=e2388]: "#74"
                      - generic [ref=e2389]: Olivia
                  - generic [ref=e2391]:
                    - generic [ref=e2392]:
                      - img [ref=e2393]
                      - generic [ref=e2395]: 05:24 AM
                    - generic [ref=e2396]:
                      - img [ref=e2397]
                      - generic [ref=e2399]: "Turn: 2.0"
                    - generic [ref=e2400]:
                      - img [ref=e2401]
                      - generic [ref=e2406]: "T: 40.00"
                    - generic [ref=e2407]:
                      - img [ref=e2408]
                      - generic [ref=e2412]: "L: 40.00"
                - listitem [ref=e2413] [cursor=pointer]:
                  - generic [ref=e2414]:
                    - generic [ref=e2416]: K
                    - generic [ref=e2417]:
                      - generic [ref=e2419]: "#75"
                      - generic [ref=e2420]: Kim
                  - generic [ref=e2422]:
                    - generic [ref=e2423]:
                      - img [ref=e2424]
                      - generic [ref=e2426]: 07:00 AM
                    - generic [ref=e2427]:
                      - img [ref=e2428]
                      - generic [ref=e2430]: "Turn: 2.0"
                    - generic [ref=e2431]:
                      - img [ref=e2432]
                      - generic [ref=e2437]: "T: 40.00"
                    - generic [ref=e2438]:
                      - img [ref=e2439]
                      - generic [ref=e2443]: "L: 40.00"
                - listitem [ref=e2444] [cursor=pointer]:
                  - generic [ref=e2445]:
                    - generic [ref=e2447]: C
                    - generic [ref=e2448]:
                      - generic [ref=e2450]: "#76"
                      - generic [ref=e2451]: Ciara
                  - generic [ref=e2453]:
                    - generic [ref=e2454]:
                      - img [ref=e2455]
                      - generic [ref=e2457]: 05:31 AM
                    - generic [ref=e2458]:
                      - img [ref=e2459]
                      - generic [ref=e2461]: "Turn: 2.0"
                    - generic [ref=e2462]:
                      - img [ref=e2463]
                      - generic [ref=e2468]: "T: 40.22"
                    - generic [ref=e2469]:
                      - img [ref=e2470]
                      - generic [ref=e2474]: "L: 20.22"
                - listitem [ref=e2475] [cursor=pointer]:
                  - generic [ref=e2476]:
                    - generic [ref=e2478]: H
                    - generic [ref=e2479]:
                      - generic [ref=e2481]: "#77"
                      - generic [ref=e2482]: Hung
                  - generic [ref=e2484]:
                    - generic [ref=e2485]:
                      - img [ref=e2486]
                      - generic [ref=e2488]: 05:30 AM
                    - generic [ref=e2489]:
                      - img [ref=e2490]
                      - generic [ref=e2492]: "Turn: 2.0"
                    - generic [ref=e2493]:
                      - img [ref=e2494]
                      - generic [ref=e2499]: "T: 45.80"
                    - generic [ref=e2500]:
                      - img [ref=e2501]
                      - generic [ref=e2505]: "L: 45.80"
                - listitem [ref=e2506] [cursor=pointer]:
                  - generic [ref=e2507]:
                    - generic [ref=e2509]: E
                    - generic [ref=e2510]:
                      - generic [ref=e2512]: "#78"
                      - generic [ref=e2513]: Evelyn
                  - generic [ref=e2515]:
                    - generic [ref=e2516]:
                      - img [ref=e2517]
                      - generic [ref=e2519]: 05:24 AM
                    - generic [ref=e2520]:
                      - img [ref=e2521]
                      - generic [ref=e2523]: "Turn: 2.0"
                    - generic [ref=e2524]:
                      - img [ref=e2525]
                      - generic [ref=e2530]: "T: 51.00"
                    - generic [ref=e2531]:
                      - img [ref=e2532]
                      - generic [ref=e2536]: "L: 51.00"
                - listitem [ref=e2537] [cursor=pointer]:
                  - generic [ref=e2538]:
                    - generic [ref=e2540]: H
                    - generic [ref=e2541]:
                      - generic [ref=e2543]: "#79"
                      - generic [ref=e2544]: Hazel
                  - generic [ref=e2546]:
                    - generic [ref=e2547]:
                      - img [ref=e2548]
                      - generic [ref=e2550]: 05:26 AM
                    - generic [ref=e2551]:
                      - img [ref=e2552]
                      - generic [ref=e2554]: "Turn: 2.0"
                    - generic [ref=e2555]:
                      - img [ref=e2556]
                      - generic [ref=e2561]: "T: 51.51"
                    - generic [ref=e2562]:
                      - img [ref=e2563]
                      - generic [ref=e2567]: "L: 51.51"
                - listitem [ref=e2568] [cursor=pointer]:
                  - generic [ref=e2569]:
                    - generic [ref=e2571]: K
                    - generic [ref=e2572]:
                      - generic [ref=e2574]: "#80"
                      - generic [ref=e2575]: Kelley
                  - generic [ref=e2577]:
                    - generic [ref=e2578]:
                      - img [ref=e2579]
                      - generic [ref=e2581]: 07:00 AM
                    - generic [ref=e2582]:
                      - img [ref=e2583]
                      - generic [ref=e2585]: "Turn: 3.0"
                    - generic [ref=e2586]:
                      - img [ref=e2587]
                      - generic [ref=e2592]: "T: 65.00"
                    - generic [ref=e2593]:
                      - img [ref=e2594]
                      - generic [ref=e2598]: "L: 25.00"
                - listitem [ref=e2599] [cursor=pointer]:
                  - generic [ref=e2600]:
                    - generic [ref=e2602]: C
                    - generic [ref=e2603]:
                      - generic [ref=e2605]: "#81"
                      - generic [ref=e2606]: Christ
                  - generic [ref=e2608]:
                    - generic [ref=e2609]:
                      - img [ref=e2610]
                      - generic [ref=e2612]: 07:00 AM
                    - generic [ref=e2613]:
                      - img [ref=e2614]
                      - generic [ref=e2616]: "Turn: 3.0"
                    - generic [ref=e2617]:
                      - img [ref=e2618]
                      - generic [ref=e2623]: "T: 67.50"
                    - generic [ref=e2624]:
                      - img [ref=e2625]
                      - generic [ref=e2629]: "L: 27.50"
                - listitem [ref=e2630] [cursor=pointer]:
                  - generic [ref=e2631]:
                    - generic [ref=e2633]: M
                    - generic [ref=e2634]:
                      - generic [ref=e2636]: "#82"
                      - generic [ref=e2637]: Mia
                  - generic [ref=e2639]:
                    - generic [ref=e2640]:
                      - img [ref=e2641]
                      - generic [ref=e2643]: 05:27 AM
                    - generic [ref=e2644]:
                      - img [ref=e2645]
                      - generic [ref=e2647]: "Turn: 3.0"
                    - generic [ref=e2648]:
                      - img [ref=e2649]
                      - generic [ref=e2654]: "T: 76.00"
                    - generic [ref=e2655]:
                      - img [ref=e2656]
                      - generic [ref=e2660]: "L: 76.00"
                - listitem [ref=e2661] [cursor=pointer]:
                  - generic [ref=e2662]:
                    - generic [ref=e2664]: D
                    - generic [ref=e2665]:
                      - generic [ref=e2667]: "#83"
                      - generic [ref=e2668]: Daria
                  - generic [ref=e2670]:
                    - generic [ref=e2671]:
                      - img [ref=e2672]
                      - generic [ref=e2674]: 07:00 AM
                    - generic [ref=e2675]:
                      - img [ref=e2676]
                      - generic [ref=e2678]: "Turn: 8.0"
                    - generic [ref=e2679]:
                      - img [ref=e2680]
                      - generic [ref=e2685]: "T: 164.00"
                    - generic [ref=e2686]:
                      - img [ref=e2687]
                      - generic [ref=e2691]: "L: 84.00"
                - listitem [ref=e2692] [cursor=pointer]:
                  - generic [ref=e2693]:
                    - generic [ref=e2695]: S
                    - generic [ref=e2696]:
                      - generic [ref=e2698]: "#84"
                      - generic [ref=e2699]: Sydney
                  - generic [ref=e2701]:
                    - generic [ref=e2702]:
                      - img [ref=e2703]
                      - generic [ref=e2705]: 05:18 AM
                    - generic [ref=e2706]:
                      - img [ref=e2707]
                      - generic [ref=e2709]: "Turn: 8.0"
                    - generic [ref=e2710]:
                      - img [ref=e2711]
                      - generic [ref=e2716]: "T: 167.10"
                    - generic [ref=e2717]:
                      - img [ref=e2718]
                      - generic [ref=e2722]: "L: 67.10000000000001"
                - listitem [ref=e2723] [cursor=pointer]:
                  - generic [ref=e2724]:
                    - generic [ref=e2726]: A
                    - generic [ref=e2727]:
                      - generic [ref=e2729]: "#85"
                      - generic [ref=e2730]: Anna
                  - generic [ref=e2732]:
                    - generic [ref=e2733]:
                      - img [ref=e2734]
                      - generic [ref=e2736]: 12:00 AM
                    - generic [ref=e2737]:
                      - img [ref=e2738]
                      - generic [ref=e2740]: "Turn: 9.0"
                    - generic [ref=e2741]:
                      - img [ref=e2742]
                      - generic [ref=e2747]: "T: 197.00"
                    - generic [ref=e2748]:
                      - img [ref=e2749]
                      - generic [ref=e2753]: "L: 8.00"
          - button "search" [ref=e2755] [cursor=pointer]:
            - img [ref=e2756]
        - generic [ref=e2759]:
          - generic [ref=e2760]:
            - list [ref=e2761]:
              - listitem [ref=e2762]:
                - button "Ready" [ref=e2763] [cursor=pointer]
              - listitem [ref=e2764]:
                - button "In Service"
              - listitem [ref=e2765]:
                - button "Paid"
              - listitem [ref=e2766]:
                - button "All" [disabled]
            - button [ref=e2767] [cursor=pointer]:
              - img [ref=e2769]
          - img [ref=e2774] [cursor=pointer]
          - list [ref=e2777]:
            - listitem [ref=e2778] [cursor=pointer]:
              - img [ref=e2779]
            - listitem [ref=e2782] [cursor=pointer]:
              - img [ref=e2783]
          - list [ref=e2787]:
            - listitem [ref=e2788] [cursor=pointer]:
              - generic [ref=e2789]:
                - generic [ref=e2790]: A
                - generic [ref=e2791]:
                  - generic [ref=e2793]: Done
                  - generic [ref=e2794]:
                    - generic [ref=e2795]: "#114"
                    - list [ref=e2796]:
                      - listitem [ref=e2797]:
                        - generic [ref=e2798]: Anna
              - generic [ref=e2799]:
                - img [ref=e2801]
                - generic [ref=e2803]: Miiii
              - generic [ref=e2804]:
                - generic [ref=e2805]:
                  - generic [ref=e2806]:
                    - generic [ref=e2808]: 04:03 AM - 04:03 AM
                    - generic [ref=e2809]:
                      - img [ref=e2810]
                      - generic [ref=e2813]: 0'
                  - generic [ref=e2816]: Ready for Payment
                - generic [ref=e2817]: $14.00
            - listitem [ref=e2818] [cursor=pointer]:
              - generic [ref=e2819]:
                - generic [ref=e2820]: C
                - generic [ref=e2821]:
                  - generic [ref=e2823]: Waiting
                  - generic [ref=e2824]:
                    - generic [ref=e2825]: "#136"
                    - list [ref=e2826]:
                      - listitem [ref=e2827]:
                        - generic [ref=e2828]: Calantha
              - generic [ref=e2829]:
                - generic [ref=e2830]:
                  - generic [ref=e2831]:
                    - generic [ref=e2833]: 05:23 AM - Now
                    - generic [ref=e2834]:
                      - img [ref=e2835]
                      - generic [ref=e2838]: 0'
                  - generic [ref=e2841]: Waiting for Service
                - generic [ref=e2842]: $0.00
            - listitem [ref=e2843] [cursor=pointer]:
              - generic [ref=e2844]:
                - generic [ref=e2845]: K
                - generic [ref=e2846]:
                  - generic [ref=e2848]: Waiting
                  - generic [ref=e2849]:
                    - generic [ref=e2850]: "#179"
                    - list [ref=e2851]:
                      - listitem [ref=e2852]:
                        - generic [ref=e2853]: Kayla
              - generic [ref=e2854]:
                - generic [ref=e2855]:
                  - generic [ref=e2856]:
                    - generic [ref=e2858]: 05:28 AM - Now
                    - generic [ref=e2859]:
                      - img [ref=e2860]
                      - generic [ref=e2863]: 0'
                  - generic [ref=e2866]: Waiting for Service
                - generic [ref=e2867]: $0.00
  - alert [ref=e2868]
```

# Test source

```ts
  3765 | 				day: '2-digit',
  3766 | 			});
  3767 | 		});
  3768 | 
  3769 | 		await expect(dateCell).toContainText(formattedToday);
  3770 | 		await expect(valueCell).toBeVisible();
  3771 | 		await expect(valueCell).toHaveText(value);
  3772 | 		await expect(dateCell).toBeVisible();
  3773 | 	},
  3774 | );
  3775 | When(
  3776 | 	'I click on the check-box {string} button',
  3777 | 	async ({ page }, item: string) => {
  3778 | 		const itemButton = page
  3779 | 			.locator('.MuiFormControlLabel-labelPlacementEnd')
  3780 | 			.getByText(item);
  3781 | 		await expect(itemButton).toBeVisible();
  3782 | 
  3783 | 		await itemButton.click();
  3784 | 	},
  3785 | );
  3786 | Then(
  3787 | 	'I should see the new Menu Category  {string}, Category Type {string}, in the Menu Categories list',
  3788 | 	async ({ page }, categoryName: string, categoryType: string) => {
  3789 | 		const categoryNameCell = page
  3790 | 			.locator('.MuiDataGrid-row')
  3791 | 			.locator('[data-field="name"]', { hasText: categoryName })
  3792 | 			.first();
  3793 | 		const categoryTypeCell = page
  3794 | 			.locator('.MuiDataGrid-row')
  3795 | 			.locator('[data-field="categoryType"]', { hasText: categoryType })
  3796 | 			.first();
  3797 | 		await expect(categoryNameCell).toBeVisible();
  3798 | 		await expect(categoryNameCell).toHaveText(categoryName);
  3799 | 		await expect(categoryTypeCell).toBeVisible();
  3800 | 		await expect(categoryTypeCell).toHaveText(categoryType);
  3801 | 	},
  3802 | );
  3803 | When('I click on the check-box Select All button', async ({ page }) => {
  3804 | 	const itemButton = page.locator('.MuiSwitch-edgeEnd');
  3805 | 	await itemButton.click();
  3806 | });
  3807 | Then(
  3808 | 	'I should see the new item {string}, Category {string}, in the Menu Items list',
  3809 | 	async ({ page }, menuItemName: string, category: string) => {
  3810 | 		const menuItemNameCell = page
  3811 | 			.locator('.MuiDataGrid-row')
  3812 | 			.locator('[data-field="name"]', { hasText: menuItemName })
  3813 | 			.first();
  3814 | 		const CategoryCell = page
  3815 | 			.locator('.MuiDataGrid-row')
  3816 | 			.locator('[data-field="categoryId"]', { hasText: category })
  3817 | 			.first();
  3818 | 		await expect(menuItemNameCell).toBeVisible();
  3819 | 		await expect(menuItemNameCell).toHaveText(menuItemName);
  3820 | 		await expect(CategoryCell).toBeVisible();
  3821 | 		await expect(CategoryCell).toHaveText(category);
  3822 | 	},
  3823 | );
  3824 | Then(
  3825 | 	'I should see the {string} Adjustment',
  3826 | 	async ({ page }, Title: string) => {
  3827 | 		const titleAdjustTurn = page.locator('.dailyTask__title');
  3828 | 
  3829 | 		await expect(titleAdjustTurn).toBeVisible();
  3830 | 		await expect(titleAdjustTurn).toHaveText(Title);
  3831 | 	},
  3832 | );
  3833 | When(
  3834 | 	'I click on the {string} in turn adjustment',
  3835 | 	async ({ page }, addJustTurn: string) => {
  3836 | 		const lateTurn = page
  3837 | 			.locator('.dailyTask')
  3838 | 			.locator('.MuiListItem-root')
  3839 | 			.filter({ hasText: new RegExp(`^${addJustTurn}$`) });
  3840 | 		await expect(lateTurn).toBeVisible();
  3841 | 		await expect(lateTurn).toHaveText(addJustTurn);
  3842 | 		await lateTurn.click();
  3843 | 		// const box = await lateTurn.boundingBox();
  3844 | 		// 	if (box) {
  3845 | 		// 		await page.mouse.move(box.x + box.width / 2, box.y + box.height / 2);
  3846 | 		// 		await page.mouse.down();
  3847 | 		// 		await page.waitForTimeout(1000);
  3848 | 		// 		await page.mouse.up();
  3849 | 		// 	}
  3850 | 	},
  3851 | );
  3852 | Then(
  3853 | 	'I should see Employee {string} with {string} in the employee list',
  3854 | 	async ({ page }, employeeName: string, expectedValue: string) => {
  3855 | 		const listEmployee = page.locator('ul.ListItemEmployee__wrap ').first();
  3856 | 		await expect(listEmployee).toBeVisible();
  3857 | 		const employeeRow = listEmployee
  3858 | 			.locator('li.xEmployeeItem')
  3859 | 			.filter({ hasText: employeeName });
  3860 | 		await expect(employeeRow).toBeVisible();
  3861 | 		const targetChip = employeeRow
  3862 | 			.locator('.xEmployeeItem__wrap .MuiChip-root')
  3863 | 			.filter({ hasText: expectedValue });
  3864 | 
> 3865 | 		await expect(targetChip).toBeVisible();
       |                            ^ Error: expect(locator).toBeVisible() failed
  3866 | 		await expect(targetChip).toContainText(expectedValue);
  3867 | 	},
  3868 | );
  3869 | When('I waiting 1s', async ({ page }) => {
  3870 | 	await page.waitForTimeout(1000);
  3871 | });
  3872 | Then(
  3873 | 	'I should see the position employee {string} is {string}',
  3874 | 	async ({ page }, employeeName: string, position: string) => {
  3875 | 		const listEmployee = page.locator('ul.ListItemEmployee__wrap ').first();
  3876 | 		await expect(listEmployee).toBeVisible();
  3877 | 
  3878 | 		const employeeRow = listEmployee
  3879 | 			.locator('li.xEmployeeItem')
  3880 | 			.filter({ hasText: employeeName });
  3881 | 		await expect(employeeRow).toBeVisible();
  3882 | 
  3883 | 		const numberPosition = employeeRow.locator('.number');
  3884 | 		await expect(numberPosition).toBeVisible();
  3885 | 		await expect(numberPosition).toHaveText(position);
  3886 | 	},
  3887 | );
  3888 | 
  3889 | Then(
  3890 | 	'I should see the employee {string} is not at position 1',
  3891 | 	async ({ page }, employeeName: string) => {
  3892 | 		const listEmployee = page.locator('ul.ListItemEmployee__wrap ').first();
  3893 | 		await expect(listEmployee).toBeVisible();
  3894 | 		const employeeRow = listEmployee
  3895 | 			.locator('li.xEmployeeItem')
  3896 | 			.filter({ hasText: employeeName });
  3897 | 		await expect(employeeRow).toBeVisible();
  3898 | 		const numberPosition = employeeRow.locator('.number');
  3899 | 		await expect(numberPosition).toBeVisible();
  3900 | 		await expect(numberPosition).not.toHaveText('#1');
  3901 | 	},
  3902 | );
  3903 | 
  3904 | Then(
  3905 | 	'I should see the header {string} in the bill render',
  3906 | 	async ({ page }, header: string) => {
  3907 | 		const billRender = page.locator('.bill-render');
  3908 | 		await expect(billRender).toBeVisible();
  3909 | 
  3910 | 		const headerElement = billRender
  3911 | 			.locator('p.header')
  3912 | 			.getByText(header, { exact: true });
  3913 | 		await expect(headerElement).toBeVisible();
  3914 | 	},
  3915 | );
  3916 | 
  3917 | Then(
  3918 | 	'I should see the detail {string} in the bill render',
  3919 | 	async ({ page }, detail: string) => {
  3920 | 		const colonIndex = detail.indexOf(':');
  3921 | 		if (colonIndex === -1) {
  3922 | 			throw new Error(
  3923 | 				`Invalid detail format: "${detail}". Expected format: "Label: Value"`,
  3924 | 			);
  3925 | 		}
  3926 | 
  3927 | 		const labelPart = detail.substring(0, colonIndex).trim(); // E.g.: "Technician Name"
  3928 | 		const expectedValue = detail.substring(colonIndex + 1).trim(); // E.g.: "Elena"
  3929 | 
  3930 | 		const infoRow = page.locator('.info-row').filter({
  3931 | 			has: page.locator('.info-label', {
  3932 | 				hasText: new RegExp(`^\\s*${labelPart}\\s*:?\\s*$`),
  3933 | 			}),
  3934 | 		});
  3935 | 
  3936 | 		await expect(infoRow).toBeVisible();
  3937 | 
  3938 | 		const valueElement = infoRow.locator('.info-value');
  3939 | 		await expect(valueElement).toBeVisible();
  3940 | 		await expect(valueElement).toContainText(expectedValue);
  3941 | 	},
  3942 | );
  3943 | 
  3944 | Then(
  3945 | 	'I should see the {string} with value {string} in the sale row detail',
  3946 | 	async ({ page }, field: string, value: string) => {
  3947 | 		const billRender = page.locator('.bill-render');
  3948 | 		await expect(billRender).toBeVisible();
  3949 | 
  3950 | 		const salesRow = billRender
  3951 | 			.locator('.sales-details .sales-row')
  3952 | 			.filter({ hasNot: billRender.locator('.total-row') })
  3953 | 			.first();
  3954 | 		await expect(salesRow).toBeVisible();
  3955 | 
  3956 | 		const fieldToSelector: Record<string, string> = {
  3957 | 			'Item Name': '.item-name',
  3958 | 			QTY: '.quantity',
  3959 | 			Tip: '.tip',
  3960 | 			Amount: '.amount',
  3961 | 		};
  3962 | 
  3963 | 		const selector = fieldToSelector[field];
  3964 | 		if (!selector) {
  3965 | 			throw new Error(
```