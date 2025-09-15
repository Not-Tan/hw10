# hw10
## json_mode_schema; Results
messages = [
  {"role":"system","content":"Return ONLY a JSON object matching the schema."},
  {"role":"user","content":"Order A-1029 by Sarah Johnson : WB-500; 2x Water Bottle ($12.50 each), CP-010; 1x Carrying Pouch ($5). Total $30. sj@example.com. "}
]
## tc_complete_currency; Test cases and Results
ex.run("Convert 100 USD to THB")
![USD to THB](screenshots/1.png)
ex.run("Convert 250 baht to euros")
![baht to euros](screenshots/2.png)
ex.run("Convert 1000000 EUR to USD")
![EUR to USD](screenshots/3.png)
ex.run("Convert 1 euros to yens")
![euros to yens](screenshots/4.png)
ex.run("Convert 9999 dollars to rupees")
![dollars to rupees](screenshots/5.png)
