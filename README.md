# irctc-bot
Research on IRCTC. Why can't normal people book tatkal tickets? 

# Booking curls
  
<details>

curl 'https://www.irctc.co.in/eticketing/protected/mapps1/altAvlEnq/TC' \
  -H 'accept: application/json, text/plain, */*' \
  -H 'accept-language: en-US,en;q=0.0' \
  -H 'authorization: Bearer 28ba394c-45f4-4707-a75f-a28c8c2d1692' \
  -H 'bmirak: webbm' \
  -H 'bmiyek: BC2382828765A1F05358C89A6038C0FF' \
  -H 'cache-control: no-cache' \
  -H 'content-language: en' \
  -H 'content-type: application/json; charset=UTF-8' \
  -b $'bm_ss=ab8e18ef4e; _gid=GA1.3.848614353.1745039630; TS018d84e5=01d83d9ce7d6fb4e4020a405a761443d6fed97c6f2f278c57b11ed693847886b5e838c9cb140de6b10ca52dcac187d18c3d7b472bb; _gcl_au=1.1.62160036.1745041395; _ga_R24JMMNBXX=GS1.1.1745041395.1.0.1745041395.60.0.0; bm_s=YAAQNUYDF1o0uCKWAQAAZ9CTTAOYgTYtvNP3VJUcfcl6vz4B4IjaLFIWQlRMfwjUwJ6efhkDQ8J9jPfrBUAFfPNRav0wMber6SDSt3UmVoVOM+J9Oywd7z5xC9onRrexDqPySpKTTWqbbHoOHcEcIbsgLz3X8tvci453JRb14yGagwpkLztjQ/9IyBUJ8E/VpFKc4IcXGnWXtYR5KzX6kanG7tnsA3QQoo5erAVauEwZUHu90uIwp9Mn0d+6iKODY4dpvaxBtzjHEzlOKBMALzsIdYho9bGHCMq8P5aQWzFtncxC73HSx4nb94S29LEdTc94fhXNLTV3u6WGDiStEPLk/ajW3V7nyUWgPd8A0Zh/TMnhTC6yZpQ0kv/djvqsx7ift0LaO5Q79SmHlwnooQqqbV4BrIMqA/qMl4ZuUmTle6T9lNLrd17YKWOE6UoOibtZupefm+wJYKg6gWadIQ==; bm_so=BAD45DE45A27169F689873389A1A82BB7952586A65292A3EAE54527244F77F26~YAAQNUYDF1s0uCKWAQAAZ9CTTAOZm709KRc4fkcke198+g+g1PSx8UnGUu+G9fHsf16sbKdiOS7O9kD9krxPsK8I85A9um9Tr+9THtXVK7fRKM/Wa46Ysen1OWZBmKKlF96CGhTHQ+Pjm8Xe6uhuoWmJ2WX4plWQ+utE/kBvrJ5TdnKUO4UNgHCB2jY/k4vWM1eNSEQLEZnb7ba/dr70JC5z5BhpRp4NOvsdPu4VKC1WK2MVpGd2jFYNUKDDYY/uNtjQZzdd0KiMTPw+DXVb2B8QY1nYGtzOOZ5ljLJxvcWftY3WdS8v9/Sx9dHM79GNpGTrYBDw9SvG6Me/6vNSqZKcHuF5EtvYW75ac3XnEN4v6pMkrj61uyu0qRDq3gjivfhLK9D2a9xulsvs3eu/aIuDwWWkh78i4oMKYyq2UBh29kl5sc34qOUQhOHwroAc2/e3hLpgghlCdmsLYl7O6KSSSg==; _ga=GA1.1.1504996631.1745039630; _ga_JSTMKS9Y3J=GS1.1.1745039631.1.1.1745041488.0.0.0; bm_lso=BAD45DE45A27169F689873389A1A82BB7952586A65292A3EAE54527244F77F26~YAAQNUYDF1s0uCKWAQAAZ9CTTAOZm709KRc4fkcke198+g+g1PSx8UnGUu+G9fHsf16sbKdiOS7O9kD9krxPsK8I85A9um9Tr+9THtXVK7fRKM/Wa46Ysen1OWZBmKKlF96CGhTHQ+Pjm8Xe6uhuoWmJ2WX4plWQ+utE/kBvrJ5TdnKUO4UNgHCB2jY/k4vWM1eNSEQLEZnb7ba/dr70JC5z5BhpRp4NOvsdPu4VKC1WK2MVpGd2jFYNUKDDYY/uNtjQZzdd0KiMTPw+DXVb2B8QY1nYGtzOOZ5ljLJxvcWftY3WdS8v9/Sx9dHM79GNpGTrYBDw9SvG6Me/6vNSqZKcHuF5EtvYW75ac3XnEN4v6pMkrj61uyu0qRDq3gjivfhLK9D2a9xulsvs3eu/aIuDwWWkh78i4oMKYyq2UBh29kl5sc34qOUQhOHwroAc2/e3hLpgghlCdmsLYl7O6KSSSg==^1745041489247; ngetAppId=dZRMlECgRX6QjJnYek1SEhlD2VqSWrchYx670hbEHr_Zs5Ta_69w\u0021-735474581; et_appVIP1=1057115658.17439.0000; _abck=D8B6F63CDAF4608955AFCC122AF2B6F6~0~YAAQNUYDF4M6uCKWAQAA6UCUTA3jgeSu4BDotOr3ZsRjBXQmoU2px82DbpbDI0/dkDd63ZNoNjQRdUJTUMPGMkVVMVCbyfRxyBeh+zqDLb/tA7+uyYC1ywYb3+YD8UryTp3QsnY075P+j0Mc3XLXixM7TmaJegvGRIINZ7DexkV+D8X/xLIZvFW3OdlHDo289+vtRfH0avHAVfcJdVLMy7kveJfYBfkHIZTOisjle0R7M6/rtWJL5oqXJr/vw/zzxENQMR5jD+/ZRZ03wh6YoYC7FSAjz3nYBX42EWQiB9cArHzI9CimVfUgWNNs2EJpZ0+6uJet4QdtJUliA5gIQcK9EZDxJtc65/NV2MDO6QeQ1Bk2BETFT3GfiyVKNA3vEt3cMuGeOrV1TCdr3er1IALOTcXQVZa38+rwVt+TpNU9PHMvnYFvdLQGKbWxquRxsTOh8JV890XiMHSdypS9Ki+WPc+tiPbYiXC62Ry/hpa4xWJVgSMgi592SR2HjdXRHhMFO8U3+TbSltnkO5KFWD8r6jRBNvoPeve/rZpFX2WV8JkQKCaETybiigifmHFhOJ08yHBa3m6HGdw+FjGwzxlPC3ktUT51qg27vdADIqUTK4gR7H/LnTdq6VBD6G8/VKFR3buKjW9Bae6e47CURQ/NjaZyQxJAHpgKwDCYIfuC4vAHQbhy8XO/N7wuFLBoUpwAAzgeBs3KKM0Hke/K+6l1ZW1VGhMIA9p+WL2xMB6OiGOkPVpa56lvF3QoaLnvF0w3AKTjDqEbP9Iw0jheshfi8z3ON+njnLtVWs1dZ7uArOMKH9vbEWitRpNsjLYZarLS9Co51AblwkD37Sn6UApAg10VGVHpAcecSuQnNetGTTbJ+Xk6ijFihxbQZpsTnsQ=~-1~-1~1745043221; bm_sz=1C014777F8FA015BACD38209C2F65F4C~YAAQNUYDF4Q6uCKWAQAA6kCUTBtibbU6jByZaI9wGxMPSbuMeTCdneMwH+FvNzSmV/cKs2kjLdBepudxUZa4maRAuytLZovP+6oln+VTzC4eWAjmiqeliA/dqLopDcY65OXDTQG1gleMkziKb1nPgDtAil4NCjmZewx6l+Aw/jXQ1udlc131rxqIuAmGqUFroOuaKKv82udEEKb7JsvMwreiCUzVxAcuE2g9PgilwDIQZHGWlejHZcQRis8cOWWfDVKvv3UH9JuTz8+0J0b+XbCVEhRIVaAV/H/hebmVxRIWQwOKhCkHW6OtgOgSE9ik2n9U5ZNt8hJHkHiY0hxmPr/GGu3bu24ZfiW6mj7Qh0O5JHX+NymiGhFw6KwzJkPIjdfFG8aZTBXzvD5eUqQYgHWDNdhmqiuNrSAsZWWpsnL4XdqQRU++QSYiBzYFnjSReZxPLI42RYos0iEArj5FJmwfdfUn0w==~4340038~4277825; _ga_SHTZYKNHG2=GS1.1.1745039630.1.1.1745041515.0.0.0; _ga_NFN218243Z=GS1.1.1745039630.1.1.1745041537.0.0.0; _ga_7K0RMWL72E=GS1.1.1745041477.1.1.1745041537.0.0.0; RT="z=1&dm=www.irctc.co.in&si=ea039a6d-d875-467f-addb-848d12641828&ss=m9nrjeng&sl=5&tt=1lay&bcn=%2F%2F684d0d49.akstat.io%2F&ld=13vjz&nu=9y8m6cy&cl=159hn"' \
  -H 'greq: GQ:9a2f301b-0467-4bf3-91b9-b0230d6f4179' \
  -H 'origin: https://www.irctc.co.in' \
  -H 'pragma: no-cache' \
  -H 'priority: u=1, i' \
  -H 'referer: https://www.irctc.co.in/nget/train-search' \
  -H 'sec-ch-ua: "Google Chrome";v="135", "Not-A.Brand";v="8", "Chromium";v="135"' \
  -H 'sec-ch-ua-mobile: ?0' \
  -H 'sec-ch-ua-platform: "Windows"' \
  -H 'sec-fetch-dest: empty' \
  -H 'sec-fetch-mode: cors' \
  -H 'sec-fetch-site: same-origin' \
  -H 'spa-csrf-token: 1745041515474-248673713' \
  -H 'user-agent: Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/135.0.0.0 Safari/537.36' \
  --data-raw '{"concessionBooking":false,"srcStn":"KYN","destStn":"PNBE","jrnyClass":"","jrnyDate":"20250420","quotaCode":"TQ","currentBooking":"false","flexiFlag":false,"handicapFlag":false,"ticketType":"E","loyaltyRedemptionBooking":false,"ftBooking":false}' ;




curl 'https://www.irctc.co.in/eticketing/protected/mapps1/altAvlEnq/TC' \
  -H 'greq: GQ:9a2f301b-0467-4bf3-91b9-b0230d6f4179' \
  -H 'sec-ch-ua-platform: "Windows"' \
  -H 'Authorization: Bearer 28ba394c-45f4-4707-a75f-a28c8c2d1692' \
  -H 'bmirak: webbm' \
  -H 'Referer: https://www.irctc.co.in/nget/train-search' \
  -H 'spa-csrf-token: 1745041515474-248673713' \
  -H 'Accept-Language: en-US,en;q=0.0' \
  -H 'sec-ch-ua: "Google Chrome";v="135", "Not-A.Brand";v="8", "Chromium";v="135"' \
  -H 'bmiyek: BC2382828765A1F05358C89A6038C0FF' \
  -H 'sec-ch-ua-mobile: ?0' \
  -H 'User-Agent: Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/135.0.0.0 Safari/537.36' \
  -H 'Accept: application/json, text/plain, */*' \
  -H 'Content-Type: application/json; charset=UTF-8' \
  -H 'Content-Language: en' \
  --data-raw '{"concessionBooking":false,"srcStn":"KYN","destStn":"PNBE","jrnyClass":"","jrnyDate":"20250420","quotaCode":"TQ","currentBooking":"false","flexiFlag":false,"handicapFlag":false,"ticketType":"E","loyaltyRedemptionBooking":false,"ftBooking":false}' ;




curl 'https://www.irctc.co.in/nget/2-es2015.3e29d1193288f9ab9c79.js' \
  -H 'accept: */*' \
  -H 'accept-language: en-US,en;q=0.9,de;q=0.8,zh-CN;q=0.7,zh;q=0.6' \
  -H 'cache-control: no-cache' \
  -b $'bm_ss=ab8e18ef4e; _gid=GA1.3.848614353.1745039630; _gcl_au=1.1.62160036.1745041395; _ga_R24JMMNBXX=GS1.1.1745041395.1.0.1745041395.60.0.0; bm_so=BAD45DE45A27169F689873389A1A82BB7952586A65292A3EAE54527244F77F26~YAAQNUYDF1s0uCKWAQAAZ9CTTAOZm709KRc4fkcke198+g+g1PSx8UnGUu+G9fHsf16sbKdiOS7O9kD9krxPsK8I85A9um9Tr+9THtXVK7fRKM/Wa46Ysen1OWZBmKKlF96CGhTHQ+Pjm8Xe6uhuoWmJ2WX4plWQ+utE/kBvrJ5TdnKUO4UNgHCB2jY/k4vWM1eNSEQLEZnb7ba/dr70JC5z5BhpRp4NOvsdPu4VKC1WK2MVpGd2jFYNUKDDYY/uNtjQZzdd0KiMTPw+DXVb2B8QY1nYGtzOOZ5ljLJxvcWftY3WdS8v9/Sx9dHM79GNpGTrYBDw9SvG6Me/6vNSqZKcHuF5EtvYW75ac3XnEN4v6pMkrj61uyu0qRDq3gjivfhLK9D2a9xulsvs3eu/aIuDwWWkh78i4oMKYyq2UBh29kl5sc34qOUQhOHwroAc2/e3hLpgghlCdmsLYl7O6KSSSg==; _ga=GA1.1.1504996631.1745039630; _ga_JSTMKS9Y3J=GS1.1.1745039631.1.1.1745041488.0.0.0; bm_lso=BAD45DE45A27169F689873389A1A82BB7952586A65292A3EAE54527244F77F26~YAAQNUYDF1s0uCKWAQAAZ9CTTAOZm709KRc4fkcke198+g+g1PSx8UnGUu+G9fHsf16sbKdiOS7O9kD9krxPsK8I85A9um9Tr+9THtXVK7fRKM/Wa46Ysen1OWZBmKKlF96CGhTHQ+Pjm8Xe6uhuoWmJ2WX4plWQ+utE/kBvrJ5TdnKUO4UNgHCB2jY/k4vWM1eNSEQLEZnb7ba/dr70JC5z5BhpRp4NOvsdPu4VKC1WK2MVpGd2jFYNUKDDYY/uNtjQZzdd0KiMTPw+DXVb2B8QY1nYGtzOOZ5ljLJxvcWftY3WdS8v9/Sx9dHM79GNpGTrYBDw9SvG6Me/6vNSqZKcHuF5EtvYW75ac3XnEN4v6pMkrj61uyu0qRDq3gjivfhLK9D2a9xulsvs3eu/aIuDwWWkh78i4oMKYyq2UBh29kl5sc34qOUQhOHwroAc2/e3hLpgghlCdmsLYl7O6KSSSg==^1745041489247; ngetAppId=dZRMlECgRX6QjJnYek1SEhlD2VqSWrchYx670hbEHr_Zs5Ta_69w\u0021-735474581; et_appVIP1=1057115658.17439.0000; _abck=D8B6F63CDAF4608955AFCC122AF2B6F6~0~YAAQNUYDF4M6uCKWAQAA6UCUTA3jgeSu4BDotOr3ZsRjBXQmoU2px82DbpbDI0/dkDd63ZNoNjQRdUJTUMPGMkVVMVCbyfRxyBeh+zqDLb/tA7+uyYC1ywYb3+YD8UryTp3QsnY075P+j0Mc3XLXixM7TmaJegvGRIINZ7DexkV+D8X/xLIZvFW3OdlHDo289+vtRfH0avHAVfcJdVLMy7kveJfYBfkHIZTOisjle0R7M6/rtWJL5oqXJr/vw/zzxENQMR5jD+/ZRZ03wh6YoYC7FSAjz3nYBX42EWQiB9cArHzI9CimVfUgWNNs2EJpZ0+6uJet4QdtJUliA5gIQcK9EZDxJtc65/NV2MDO6QeQ1Bk2BETFT3GfiyVKNA3vEt3cMuGeOrV1TCdr3er1IALOTcXQVZa38+rwVt+TpNU9PHMvnYFvdLQGKbWxquRxsTOh8JV890XiMHSdypS9Ki+WPc+tiPbYiXC62Ry/hpa4xWJVgSMgi592SR2HjdXRHhMFO8U3+TbSltnkO5KFWD8r6jRBNvoPeve/rZpFX2WV8JkQKCaETybiigifmHFhOJ08yHBa3m6HGdw+FjGwzxlPC3ktUT51qg27vdADIqUTK4gR7H/LnTdq6VBD6G8/VKFR3buKjW9Bae6e47CURQ/NjaZyQxJAHpgKwDCYIfuC4vAHQbhy8XO/N7wuFLBoUpwAAzgeBs3KKM0Hke/K+6l1ZW1VGhMIA9p+WL2xMB6OiGOkPVpa56lvF3QoaLnvF0w3AKTjDqEbP9Iw0jheshfi8z3ON+njnLtVWs1dZ7uArOMKH9vbEWitRpNsjLYZarLS9Co51AblwkD37Sn6UApAg10VGVHpAcecSuQnNetGTTbJ+Xk6ijFihxbQZpsTnsQ=~-1~-1~1745043221; bm_sz=1C014777F8FA015BACD38209C2F65F4C~YAAQNUYDF4Q6uCKWAQAA6kCUTBtibbU6jByZaI9wGxMPSbuMeTCdneMwH+FvNzSmV/cKs2kjLdBepudxUZa4maRAuytLZovP+6oln+VTzC4eWAjmiqeliA/dqLopDcY65OXDTQG1gleMkziKb1nPgDtAil4NCjmZewx6l+Aw/jXQ1udlc131rxqIuAmGqUFroOuaKKv82udEEKb7JsvMwreiCUzVxAcuE2g9PgilwDIQZHGWlejHZcQRis8cOWWfDVKvv3UH9JuTz8+0J0b+XbCVEhRIVaAV/H/hebmVxRIWQwOKhCkHW6OtgOgSE9ik2n9U5ZNt8hJHkHiY0hxmPr/GGu3bu24ZfiW6mj7Qh0O5JHX+NymiGhFw6KwzJkPIjdfFG8aZTBXzvD5eUqQYgHWDNdhmqiuNrSAsZWWpsnL4XdqQRU++QSYiBzYFnjSReZxPLI42RYos0iEArj5FJmwfdfUn0w==~4340038~4277825; _ga_SHTZYKNHG2=GS1.1.1745039630.1.1.1745041515.0.0.0; _ga_NFN218243Z=GS1.1.1745039630.1.1.1745041537.0.0.0; _ga_7K0RMWL72E=GS1.1.1745041477.1.1.1745041537.0.0.0; RT="z=1&dm=www.irctc.co.in&si=ea039a6d-d875-467f-addb-848d12641828&ss=m9nrjeng&sl=5&tt=1lay&bcn=%2F%2F684d0d49.akstat.io%2F&ld=13vjz&nu=9y8m6cy&cl=159hn"; TS018d84e5=01d83d9ce78206a02c312d3e325088361666f560be2ac8f71d3d44dc3efb51c9726d32c3e5f6105be3e1cf7bf5d8a2154746d67548; bm_s=YAAQN0YDF9WoOkeWAQAAD/mUTAOjoUaM9MDp0uS69SUDcZOr/QhpYduXhy4DxYt+I0zzITLV9DPqVwuYwLeQc8bEBh4FqOb/pK6MffoJ0jFr0Qp6xBV3OOq+vF/bvIJ5qe/wRf8gqgAxRieFjGKinySWWk3dd8VKrZGWKipzl8Qgll4inzBNqGaxsbNVSORvOiDRE6EQUnsXOC+b5YDuhiTDQiz7/k622I2qjuVRUSKMN1lJt/2FO3K+yNiPRVLGGDdQ84Dm8/M529Gj6TgmKa8mw0CAIZWxLedzGeuvE0WtwlELsm6ECnHVT/KFYm1Zj7rZmfSVuSWbBT1lDT0Kq6DdX34Ga7wWHtLNY/C6khXpfod9HCpC9moav6TaJqOXVKDYbIZGefHZkbtZP7Ggqi5CT+R6oi4UmPgoX1ML8oRZ4g3uupCnw5bxnEXo729YpbHh3E9oV7bWhnZZr4a2yQ==' \
  -H 'pragma: no-cache' \
  -H 'priority: i' \
  -H 'referer: https://www.irctc.co.in/nget/train-search' \
  -H 'sec-ch-ua: "Google Chrome";v="135", "Not-A.Brand";v="8", "Chromium";v="135"' \
  -H 'sec-ch-ua-mobile: ?0' \
  -H 'sec-ch-ua-platform: "Windows"' \
  -H 'sec-fetch-dest: empty' \
  -H 'sec-fetch-mode: no-cors' \
  -H 'sec-fetch-site: same-origin' \
  -H 'user-agent: Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/135.0.0.0 Safari/537.36' ;




curl 'https://www.irctc.co.in/nget/8-es2015.08d705ed6033b9fd74b3.js' \
  -H 'accept: */*' \
  -H 'accept-language: en-US,en;q=0.9,de;q=0.8,zh-CN;q=0.7,zh;q=0.6' \
  -H 'cache-control: no-cache' \
  -b $'bm_ss=ab8e18ef4e; _gid=GA1.3.848614353.1745039630; _gcl_au=1.1.62160036.1745041395; _ga_R24JMMNBXX=GS1.1.1745041395.1.0.1745041395.60.0.0; bm_so=BAD45DE45A27169F689873389A1A82BB7952586A65292A3EAE54527244F77F26~YAAQNUYDF1s0uCKWAQAAZ9CTTAOZm709KRc4fkcke198+g+g1PSx8UnGUu+G9fHsf16sbKdiOS7O9kD9krxPsK8I85A9um9Tr+9THtXVK7fRKM/Wa46Ysen1OWZBmKKlF96CGhTHQ+Pjm8Xe6uhuoWmJ2WX4plWQ+utE/kBvrJ5TdnKUO4UNgHCB2jY/k4vWM1eNSEQLEZnb7ba/dr70JC5z5BhpRp4NOvsdPu4VKC1WK2MVpGd2jFYNUKDDYY/uNtjQZzdd0KiMTPw+DXVb2B8QY1nYGtzOOZ5ljLJxvcWftY3WdS8v9/Sx9dHM79GNpGTrYBDw9SvG6Me/6vNSqZKcHuF5EtvYW75ac3XnEN4v6pMkrj61uyu0qRDq3gjivfhLK9D2a9xulsvs3eu/aIuDwWWkh78i4oMKYyq2UBh29kl5sc34qOUQhOHwroAc2/e3hLpgghlCdmsLYl7O6KSSSg==; _ga=GA1.1.1504996631.1745039630; _ga_JSTMKS9Y3J=GS1.1.1745039631.1.1.1745041488.0.0.0; bm_lso=BAD45DE45A27169F689873389A1A82BB7952586A65292A3EAE54527244F77F26~YAAQNUYDF1s0uCKWAQAAZ9CTTAOZm709KRc4fkcke198+g+g1PSx8UnGUu+G9fHsf16sbKdiOS7O9kD9krxPsK8I85A9um9Tr+9THtXVK7fRKM/Wa46Ysen1OWZBmKKlF96CGhTHQ+Pjm8Xe6uhuoWmJ2WX4plWQ+utE/kBvrJ5TdnKUO4UNgHCB2jY/k4vWM1eNSEQLEZnb7ba/dr70JC5z5BhpRp4NOvsdPu4VKC1WK2MVpGd2jFYNUKDDYY/uNtjQZzdd0KiMTPw+DXVb2B8QY1nYGtzOOZ5ljLJxvcWftY3WdS8v9/Sx9dHM79GNpGTrYBDw9SvG6Me/6vNSqZKcHuF5EtvYW75ac3XnEN4v6pMkrj61uyu0qRDq3gjivfhLK9D2a9xulsvs3eu/aIuDwWWkh78i4oMKYyq2UBh29kl5sc34qOUQhOHwroAc2/e3hLpgghlCdmsLYl7O6KSSSg==^1745041489247; ngetAppId=dZRMlECgRX6QjJnYek1SEhlD2VqSWrchYx670hbEHr_Zs5Ta_69w\u0021-735474581; et_appVIP1=1057115658.17439.0000; _abck=D8B6F63CDAF4608955AFCC122AF2B6F6~0~YAAQNUYDF4M6uCKWAQAA6UCUTA3jgeSu4BDotOr3ZsRjBXQmoU2px82DbpbDI0/dkDd63ZNoNjQRdUJTUMPGMkVVMVCbyfRxyBeh+zqDLb/tA7+uyYC1ywYb3+YD8UryTp3QsnY075P+j0Mc3XLXixM7TmaJegvGRIINZ7DexkV+D8X/xLIZvFW3OdlHDo289+vtRfH0avHAVfcJdVLMy7kveJfYBfkHIZTOisjle0R7M6/rtWJL5oqXJr/vw/zzxENQMR5jD+/ZRZ03wh6YoYC7FSAjz3nYBX42EWQiB9cArHzI9CimVfUgWNNs2EJpZ0+6uJet4QdtJUliA5gIQcK9EZDxJtc65/NV2MDO6QeQ1Bk2BETFT3GfiyVKNA3vEt3cMuGeOrV1TCdr3er1IALOTcXQVZa38+rwVt+TpNU9PHMvnYFvdLQGKbWxquRxsTOh8JV890XiMHSdypS9Ki+WPc+tiPbYiXC62Ry/hpa4xWJVgSMgi592SR2HjdXRHhMFO8U3+TbSltnkO5KFWD8r6jRBNvoPeve/rZpFX2WV8JkQKCaETybiigifmHFhOJ08yHBa3m6HGdw+FjGwzxlPC3ktUT51qg27vdADIqUTK4gR7H/LnTdq6VBD6G8/VKFR3buKjW9Bae6e47CURQ/NjaZyQxJAHpgKwDCYIfuC4vAHQbhy8XO/N7wuFLBoUpwAAzgeBs3KKM0Hke/K+6l1ZW1VGhMIA9p+WL2xMB6OiGOkPVpa56lvF3QoaLnvF0w3AKTjDqEbP9Iw0jheshfi8z3ON+njnLtVWs1dZ7uArOMKH9vbEWitRpNsjLYZarLS9Co51AblwkD37Sn6UApAg10VGVHpAcecSuQnNetGTTbJ+Xk6ijFihxbQZpsTnsQ=~-1~-1~1745043221; bm_sz=1C014777F8FA015BACD38209C2F65F4C~YAAQNUYDF4Q6uCKWAQAA6kCUTBtibbU6jByZaI9wGxMPSbuMeTCdneMwH+FvNzSmV/cKs2kjLdBepudxUZa4maRAuytLZovP+6oln+VTzC4eWAjmiqeliA/dqLopDcY65OXDTQG1gleMkziKb1nPgDtAil4NCjmZewx6l+Aw/jXQ1udlc131rxqIuAmGqUFroOuaKKv82udEEKb7JsvMwreiCUzVxAcuE2g9PgilwDIQZHGWlejHZcQRis8cOWWfDVKvv3UH9JuTz8+0J0b+XbCVEhRIVaAV/H/hebmVxRIWQwOKhCkHW6OtgOgSE9ik2n9U5ZNt8hJHkHiY0hxmPr/GGu3bu24ZfiW6mj7Qh0O5JHX+NymiGhFw6KwzJkPIjdfFG8aZTBXzvD5eUqQYgHWDNdhmqiuNrSAsZWWpsnL4XdqQRU++QSYiBzYFnjSReZxPLI42RYos0iEArj5FJmwfdfUn0w==~4340038~4277825; _ga_SHTZYKNHG2=GS1.1.1745039630.1.1.1745041515.0.0.0; _ga_NFN218243Z=GS1.1.1745039630.1.1.1745041537.0.0.0; _ga_7K0RMWL72E=GS1.1.1745041477.1.1.1745041537.0.0.0; RT="z=1&dm=www.irctc.co.in&si=ea039a6d-d875-467f-addb-848d12641828&ss=m9nrjeng&sl=5&tt=1lay&bcn=%2F%2F684d0d49.akstat.io%2F&ld=13vjz&nu=9y8m6cy&cl=159hn"; TS018d84e5=01d83d9ce78206a02c312d3e325088361666f560be2ac8f71d3d44dc3efb51c9726d32c3e5f6105be3e1cf7bf5d8a2154746d67548; bm_s=YAAQN0YDF9WoOkeWAQAAD/mUTAOjoUaM9MDp0uS69SUDcZOr/QhpYduXhy4DxYt+I0zzITLV9DPqVwuYwLeQc8bEBh4FqOb/pK6MffoJ0jFr0Qp6xBV3OOq+vF/bvIJ5qe/wRf8gqgAxRieFjGKinySWWk3dd8VKrZGWKipzl8Qgll4inzBNqGaxsbNVSORvOiDRE6EQUnsXOC+b5YDuhiTDQiz7/k622I2qjuVRUSKMN1lJt/2FO3K+yNiPRVLGGDdQ84Dm8/M529Gj6TgmKa8mw0CAIZWxLedzGeuvE0WtwlELsm6ECnHVT/KFYm1Zj7rZmfSVuSWbBT1lDT0Kq6DdX34Ga7wWHtLNY/C6khXpfod9HCpC9moav6TaJqOXVKDYbIZGefHZkbtZP7Ggqi5CT+R6oi4UmPgoX1ML8oRZ4g3uupCnw5bxnEXo729YpbHh3E9oV7bWhnZZr4a2yQ==' \
  -H 'pragma: no-cache' \
  -H 'priority: i' \
  -H 'referer: https://www.irctc.co.in/nget/train-search' \
  -H 'sec-ch-ua: "Google Chrome";v="135", "Not-A.Brand";v="8", "Chromium";v="135"' \
  -H 'sec-ch-ua-mobile: ?0' \
  -H 'sec-ch-ua-platform: "Windows"' \
  -H 'sec-fetch-dest: empty' \
  -H 'sec-fetch-mode: no-cors' \
  -H 'sec-fetch-site: same-origin' \
  -H 'user-agent: Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/135.0.0.0 Safari/537.36' ;




curl 'https://www.irctc.co.in/nget/2-es2015.3e29d1193288f9ab9c79.js' \
  -H 'sec-ch-ua-platform: "Windows"' \
  -H 'Referer: https://www.irctc.co.in/nget/train-search' \
  -H 'User-Agent: Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/135.0.0.0 Safari/537.36' \
  -H 'sec-ch-ua: "Google Chrome";v="135", "Not-A.Brand";v="8", "Chromium";v="135"' \
  -H 'sec-ch-ua-mobile: ?0' ;




curl 'https://www.irctc.co.in/nget/8-es2015.08d705ed6033b9fd74b3.js' \
  -H 'sec-ch-ua-platform: "Windows"' \
  -H 'Referer: https://www.irctc.co.in/nget/train-search' \
  -H 'User-Agent: Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/135.0.0.0 Safari/537.36' \
  -H 'sec-ch-ua: "Google Chrome";v="135", "Not-A.Brand";v="8", "Chromium";v="135"' \
  -H 'sec-ch-ua-mobile: ?0' ;




curl 'https://securepubads.g.doubleclick.net/gampad/ads?pvsid=632509865837418&correlator=4002469224131892&eid=95353385%2C31091816%2C95355263%2C83321073%2C31086809%2C31061691%2C31061692&output=ldjh&gdfp_req=1&vrg=202504160101&ptt=17&impl=fifs&iu_parts=37179215%2CGPT_NWEB_TRAIN_LIST_TOP%2CGPT_NWEB_TRAIN_LIST_BOTTOM%2CGPT_NWEB_TRAIN_LIST_LEFT%2CGPT_NWEB_TRAIN_LIST_LEFT_2&enc_prev_ius=%2F0%2F1%2C%2F0%2F2%2C%2F0%2F3%2C%2F0%2F4&prev_iu_szs=320x50%2C320x50%2C300x250%7C300x600%7C160x600%7C120x600%2C300x250%7C300x600%7C160x600%7C120x600&ifi=16&didk=3954982453~3954975278~3954976359~3955182263&dids=div-gpt-ad-509513-0~div-gpt-ad-509514-0~div-gpt-ad-509515-0~div-gpt-ad-509516-0&adfs=2570438994~2006877487~1616168037~1631822672&sfv=1-0-41&sc=1&cookie_enabled=1&abxe=1&dt=1745041563343&lmt=1744719295&adxs=-12245933%2C-12245933%2C-12245933%2C-12245933&adys=-12245933%2C-12245933%2C-12245933%2C-12245933&biw=1203&bih=912&scr_x=0&scr_y=0&btvi=-1%7C-1%7C-1%7C-1&ucis=g%7Ch%7Ci%7Cj&oid=2&u_his=38&u_h=864&u_w=1536&u_ah=816&u_aw=1536&u_cd=24&u_sd=1&u_tz=330&dmc=8&bc=31&nvt=1&uach=WyJXaW5kb3dzIiwiMTkuMC4wIiwieDg2IiwiIiwiMTM1LjAuNzA0OS45NiIsbnVsbCwwLG51bGwsIjY0IixbWyJHb29nbGUgQ2hyb21lIiwiMTM1LjAuNzA0OS45NiJdLFsiTm90LUEuQnJhbmQiLCI4LjAuMC4wIl0sWyJDaHJvbWl1bSIsIjEzNS4wLjcwNDkuOTYiXV0sMF0.&uas=3&url=https%3A%2F%2Fwww.irctc.co.in%2Fnget%2Fbooking%2Ftrain-list&ref=https%3A%2F%2Fwww.irctc.co.in%2Fnget%2Ferror&rumc=632509865837418&rume=1&vis=1&psz=887x62%7C887x103%7C300x1119%7C300x1119&msz=0x0%7C0x0%7C0x0%7C0x0&fws=128%2C128%2C128%2C128&ohw=0%2C0%2C0%2C0&topics=3&tps=3&htps=10&nt=1&psd=WzMxLFtdLG51bGwsM10.&dlt=1745041486247&idt=1661&prev_scp=Destination%3DPNBE%252CPPTA%26Gender%3DM%26Age%3D66%26Source%3DBDTS%252CKYN%26Journey_Date%3D20042025%7CDestination%3DPNBE%252CPPTA%26Gender%3DM%26Age%3D66%26Source%3DBDTS%252CKYN%26Journey_Date%3D20042025%7CDestination%3DPNBE%252CPPTA%26Gender%3DM%26Age%3D66%26Source%3DBDTS%252CKYN%7CDestination%3DPNBE%252CPPTA%26Gender%3DM%26Age%3D66%26Source%3DBDTS%252CKYN&adks=2776654081%2C594275090%2C1030543766%2C3032283664&frm=20&eoidce=1&td=1&egid=16524&tan=6156e5d4-379d-4b6e-8367-3ad443808c9f%2C6156e5d4-379d-4b6e-8367-3ad443808ca0%2C6156e5d4-379d-4b6e-8367-3ad443808ca1%2C6156e5d4-379d-4b6e-8367-3ad443808ca2&tdf=2' \
  -H 'sec-ch-ua-platform: "Windows"' \
  -H 'Referer: https://www.irctc.co.in/' \
  -H 'User-Agent: Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/135.0.0.0 Safari/537.36' \
  -H 'Accept: */*' \
  -H 'sec-ch-ua: "Google Chrome";v="135", "Not-A.Brand";v="8", "Chromium";v="135"' \
  -H 'sec-ch-ua-mobile: ?0' ;




curl 'https://securepubads.g.doubleclick.net/gampad/ads?pvsid=632509865837418&correlator=4002469224131892&eid=95353385%2C31091816%2C95355263%2C83321073%2C31086809%2C31061691%2C31061692&output=ldjh&gdfp_req=1&vrg=202504160101&ptt=17&impl=fifs&iu_parts=37179215%2CGPT_NWEB_TRAIN_LIST_TOP%2CGPT_NWEB_TRAIN_LIST_BOTTOM%2CGPT_NWEB_TRAIN_LIST_LEFT%2CGPT_NWEB_TRAIN_LIST_LEFT_2&enc_prev_ius=%2F0%2F1%2C%2F0%2F2%2C%2F0%2F3%2C%2F0%2F4&prev_iu_szs=320x50%2C320x50%2C300x250%7C300x600%7C160x600%7C120x600%2C300x250%7C300x600%7C160x600%7C120x600&ifi=16&didk=3954982453~3954975278~3954976359~3955182263&dids=div-gpt-ad-509513-0~div-gpt-ad-509514-0~div-gpt-ad-509515-0~div-gpt-ad-509516-0&adfs=2570438994~2006877487~1616168037~1631822672&sfv=1-0-41&sc=1&cookie_enabled=1&abxe=1&dt=1745041563343&lmt=1744719295&adxs=-12245933%2C-12245933%2C-12245933%2C-12245933&adys=-12245933%2C-12245933%2C-12245933%2C-12245933&biw=1203&bih=912&scr_x=0&scr_y=0&btvi=-1%7C-1%7C-1%7C-1&ucis=g%7Ch%7Ci%7Cj&oid=2&u_his=38&u_h=864&u_w=1536&u_ah=816&u_aw=1536&u_cd=24&u_sd=1&u_tz=330&dmc=8&bc=31&nvt=1&uach=WyJXaW5kb3dzIiwiMTkuMC4wIiwieDg2IiwiIiwiMTM1LjAuNzA0OS45NiIsbnVsbCwwLG51bGwsIjY0IixbWyJHb29nbGUgQ2hyb21lIiwiMTM1LjAuNzA0OS45NiJdLFsiTm90LUEuQnJhbmQiLCI4LjAuMC4wIl0sWyJDaHJvbWl1bSIsIjEzNS4wLjcwNDkuOTYiXV0sMF0.&uas=3&url=https%3A%2F%2Fwww.irctc.co.in%2Fnget%2Fbooking%2Ftrain-list&ref=https%3A%2F%2Fwww.irctc.co.in%2Fnget%2Ferror&rumc=632509865837418&rume=1&vis=1&psz=887x62%7C887x103%7C300x1119%7C300x1119&msz=0x0%7C0x0%7C0x0%7C0x0&fws=128%2C128%2C128%2C128&ohw=0%2C0%2C0%2C0&topics=3&tps=3&htps=10&nt=1&psd=WzMxLFtdLG51bGwsM10.&dlt=1745041486247&idt=1661&prev_scp=Destination%3DPNBE%252CPPTA%26Gender%3DM%26Age%3D66%26Source%3DBDTS%252CKYN%26Journey_Date%3D20042025%7CDestination%3DPNBE%252CPPTA%26Gender%3DM%26Age%3D66%26Source%3DBDTS%252CKYN%26Journey_Date%3D20042025%7CDestination%3DPNBE%252CPPTA%26Gender%3DM%26Age%3D66%26Source%3DBDTS%252CKYN%7CDestination%3DPNBE%252CPPTA%26Gender%3DM%26Age%3D66%26Source%3DBDTS%252CKYN&adks=2776654081%2C594275090%2C1030543766%2C3032283664&frm=20&eoidce=1&td=1&egid=16524&tan=6156e5d4-379d-4b6e-8367-3ad443808c9f%2C6156e5d4-379d-4b6e-8367-3ad443808ca0%2C6156e5d4-379d-4b6e-8367-3ad443808ca1%2C6156e5d4-379d-4b6e-8367-3ad443808ca2&tdf=2' \
  -H 'sec-ch-ua-platform: "Windows"' \
  -H 'Referer: https://www.irctc.co.in/' \
  -H 'User-Agent: Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/135.0.0.0 Safari/537.36' \
  -H 'sec-ch-ua: "Google Chrome";v="135", "Not-A.Brand";v="8", "Chromium";v="135"' \
  -H 'sec-ch-ua-mobile: ?0' ;




curl 'https://www.irctc.co.in/nget/assets/images/security.png' \
  -H 'sec-ch-ua-platform: "Windows"' \
  -H 'Referer: https://www.irctc.co.in/nget/booking/train-list' \
  -H 'User-Agent: Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/135.0.0.0 Safari/537.36' \
  -H 'sec-ch-ua: "Google Chrome";v="135", "Not-A.Brand";v="8", "Chromium";v="135"' \
  -H 'sec-ch-ua-mobile: ?0' ;




curl 'https://www.google-analytics.com/g/collect?v=2&tid=G-NFN218243Z&gtm=45je54g3v872522363za200zb9117897900&_p=1745041486402&gcd=13l3l3l3l1l1&npa=0&dma=0&tag_exp=102803279~102813109~102887800~102926062~103027016~103051953~103055465~103077950~103106314~103106316&cid=1504996631.1745039630&ul=en-us&sr=1536x864&uaa=x86&uab=64&uafvl=Google%2520Chrome%3B135.0.7049.96%7CNot-A.Brand%3B8.0.0.0%7CChromium%3B135.0.7049.96&uamb=0&uam=&uap=Windows&uapv=19.0.0&uaw=0&are=1&frm=0&pscdl=noapi&_eu=AEAAAAI&dl=https%3A%2F%2Fwww.irctc.co.in%2Fnget%2Fbooking%2Ftrain-list&dr=https%3A%2F%2Fwww.irctc.co.in%2Fnget%2Ftrain-search&sid=1745039630&sct=1&seg=1&dt=IRCTC%20Next%20Generation%20eTicketing%20System&_s=5&tfd=82209' \
  -H 'accept: */*' \
  -H 'accept-language: en-US,en;q=0.9,de;q=0.8,zh-CN;q=0.7,zh;q=0.6' \
  -H 'cache-control: no-cache' \
  -H 'content-type: text/plain;charset=UTF-8' \
  -b 'ar_debug=1' \
  -H 'origin: https://www.irctc.co.in' \
  -H 'pragma: no-cache' \
  -H 'priority: u=1, i' \
  -H 'referer: https://www.irctc.co.in/' \
  -H 'sec-ch-ua: "Google Chrome";v="135", "Not-A.Brand";v="8", "Chromium";v="135"' \
  -H 'sec-ch-ua-mobile: ?0' \
  -H 'sec-ch-ua-platform: "Windows"' \
  -H 'sec-fetch-dest: empty' \
  -H 'sec-fetch-mode: no-cors' \
  -H 'sec-fetch-site: cross-site' \
  -H 'sec-fetch-storage-access: active' \
  -H 'user-agent: Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/135.0.0.0 Safari/537.36' \
  --data-raw $'en=page_view&_et=17127\r\nen=scroll&epn.percent_scrolled=90&_et=1692' ;




curl 'https://www.google-analytics.com/g/collect?v=2&tid=G-NFN218243Z&gtm=45je54g3v872522363za200zb9117897900&_p=1745041486402&gcd=13l3l3l3l1l1&npa=0&dma=0&tag_exp=102803279~102813109~102887800~102926062~103027016~103051953~103055465~103077950~103106314~103106316&cid=1504996631.1745039630&ul=en-us&sr=1536x864&uaa=x86&uab=64&uafvl=Google%2520Chrome%3B135.0.7049.96%7CNot-A.Brand%3B8.0.0.0%7CChromium%3B135.0.7049.96&uamb=0&uam=&uap=Windows&uapv=19.0.0&uaw=0&are=1&frm=0&pscdl=noapi&_eu=AEAAAAI&dl=https%3A%2F%2Fwww.irctc.co.in%2Fnget%2Fbooking%2Ftrain-list&dr=https%3A%2F%2Fwww.irctc.co.in%2Fnget%2Ftrain-search&sid=1745039630&sct=1&seg=1&dt=IRCTC%20Next%20Generation%20eTicketing%20System&_s=5&tfd=82209' \
  -H 'sec-ch-ua-platform: "Windows"' \
  -H 'Referer: https://www.irctc.co.in/' \
  -H 'User-Agent: Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/135.0.0.0 Safari/537.36' \
  -H 'sec-ch-ua: "Google Chrome";v="135", "Not-A.Brand";v="8", "Chromium";v="135"' \
  -H 'Content-Type: text/plain;charset=UTF-8' \
  -H 'sec-ch-ua-mobile: ?0' \
  --data-raw $'en=page_view&_et=17127\r\nen=scroll&epn.percent_scrolled=90&_et=1692' ;




curl 'https://www.google-analytics.com/g/collect?v=2&tid=G-7K0RMWL72E&gtm=45je54g3v9116751228za200&_p=1745041486402&gcd=13l3l3l3l1l1&npa=0&dma=0&tag_exp=102803279~102813109~102887800~102926062~103027016~103051953~103055465~103077950~103106314~103106316&cid=1504996631.1745039630&ul=en-us&sr=1536x864&uaa=x86&uab=64&uafvl=Google%2520Chrome%3B135.0.7049.96%7CNot-A.Brand%3B8.0.0.0%7CChromium%3B135.0.7049.96&uamb=0&uam=&uap=Windows&uapv=19.0.0&uaw=0&are=1&frm=0&pscdl=noapi&_eu=AEAIAAI&dl=https%3A%2F%2Fwww.irctc.co.in%2Fnget%2Fbooking%2Ftrain-list&dr=https%3A%2F%2Fwww.irctc.co.in%2Fnget%2Ftrain-search&sid=1745041477&sct=1&seg=1&dt=IRCTC%20Next%20Generation%20eTicketing%20System&_s=6&tfd=82217' \
  -H 'accept: */*' \
  -H 'accept-language: en-US,en;q=0.9,de;q=0.8,zh-CN;q=0.7,zh;q=0.6' \
  -H 'cache-control: no-cache' \
  -H 'content-type: text/plain;charset=UTF-8' \
  -b 'ar_debug=1' \
  -H 'origin: https://www.irctc.co.in' \
  -H 'pragma: no-cache' \
  -H 'priority: u=1, i' \
  -H 'referer: https://www.irctc.co.in/' \
  -H 'sec-ch-ua: "Google Chrome";v="135", "Not-A.Brand";v="8", "Chromium";v="135"' \
  -H 'sec-ch-ua-mobile: ?0' \
  -H 'sec-ch-ua-platform: "Windows"' \
  -H 'sec-fetch-dest: empty' \
  -H 'sec-fetch-mode: no-cors' \
  -H 'sec-fetch-site: cross-site' \
  -H 'sec-fetch-storage-access: active' \
  -H 'user-agent: Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/135.0.0.0 Safari/537.36' \
  --data-raw $'en=page_view&_et=17129\r\nen=scroll&epn.percent_scrolled=90&_et=1692' ;




curl 'https://www.google-analytics.com/g/collect?v=2&tid=G-7K0RMWL72E&gtm=45je54g3v9116751228za200&_p=1745041486402&gcd=13l3l3l3l1l1&npa=0&dma=0&tag_exp=102803279~102813109~102887800~102926062~103027016~103051953~103055465~103077950~103106314~103106316&cid=1504996631.1745039630&ul=en-us&sr=1536x864&uaa=x86&uab=64&uafvl=Google%2520Chrome%3B135.0.7049.96%7CNot-A.Brand%3B8.0.0.0%7CChromium%3B135.0.7049.96&uamb=0&uam=&uap=Windows&uapv=19.0.0&uaw=0&are=1&frm=0&pscdl=noapi&_eu=AEAIAAI&dl=https%3A%2F%2Fwww.irctc.co.in%2Fnget%2Fbooking%2Ftrain-list&dr=https%3A%2F%2Fwww.irctc.co.in%2Fnget%2Ftrain-search&sid=1745041477&sct=1&seg=1&dt=IRCTC%20Next%20Generation%20eTicketing%20System&_s=6&tfd=82217' \
  -H 'sec-ch-ua-platform: "Windows"' \
  -H 'Referer: https://www.irctc.co.in/' \
  -H 'User-Agent: Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/135.0.0.0 Safari/537.36' \
  -H 'sec-ch-ua: "Google Chrome";v="135", "Not-A.Brand";v="8", "Chromium";v="135"' \
  -H 'Content-Type: text/plain;charset=UTF-8' \
  -H 'sec-ch-ua-mobile: ?0' \
  --data-raw $'en=page_view&_et=17129\r\nen=scroll&epn.percent_scrolled=90&_et=1692' ;




curl 'https://www.irctc.co.in/eticketing/protected/mapps1/avlFarenquiry/13202/20250420/KYN/PNBE/SL/TQ/N' \
  -H 'accept: application/json, text/plain, */*' \
  -H 'accept-language: en-US,en;q=0.0' \
  -H 'authorization: Bearer 28ba394c-45f4-4707-a75f-a28c8c2d1692' \
  -H 'bmirak: webbm' \
  -H 'bmiyek: BC2382828765A1F05358C89A6038C0FF' \
  -H 'cache-control: no-cache' \
  -H 'content-language: en' \
  -H 'content-type: application/json; charset=UTF-8' \
  -b $'bm_ss=ab8e18ef4e; _gid=GA1.3.848614353.1745039630; _gcl_au=1.1.62160036.1745041395; _ga_R24JMMNBXX=GS1.1.1745041395.1.0.1745041395.60.0.0; bm_so=BAD45DE45A27169F689873389A1A82BB7952586A65292A3EAE54527244F77F26~YAAQNUYDF1s0uCKWAQAAZ9CTTAOZm709KRc4fkcke198+g+g1PSx8UnGUu+G9fHsf16sbKdiOS7O9kD9krxPsK8I85A9um9Tr+9THtXVK7fRKM/Wa46Ysen1OWZBmKKlF96CGhTHQ+Pjm8Xe6uhuoWmJ2WX4plWQ+utE/kBvrJ5TdnKUO4UNgHCB2jY/k4vWM1eNSEQLEZnb7ba/dr70JC5z5BhpRp4NOvsdPu4VKC1WK2MVpGd2jFYNUKDDYY/uNtjQZzdd0KiMTPw+DXVb2B8QY1nYGtzOOZ5ljLJxvcWftY3WdS8v9/Sx9dHM79GNpGTrYBDw9SvG6Me/6vNSqZKcHuF5EtvYW75ac3XnEN4v6pMkrj61uyu0qRDq3gjivfhLK9D2a9xulsvs3eu/aIuDwWWkh78i4oMKYyq2UBh29kl5sc34qOUQhOHwroAc2/e3hLpgghlCdmsLYl7O6KSSSg==; _ga=GA1.1.1504996631.1745039630; _ga_JSTMKS9Y3J=GS1.1.1745039631.1.1.1745041488.0.0.0; bm_lso=BAD45DE45A27169F689873389A1A82BB7952586A65292A3EAE54527244F77F26~YAAQNUYDF1s0uCKWAQAAZ9CTTAOZm709KRc4fkcke198+g+g1PSx8UnGUu+G9fHsf16sbKdiOS7O9kD9krxPsK8I85A9um9Tr+9THtXVK7fRKM/Wa46Ysen1OWZBmKKlF96CGhTHQ+Pjm8Xe6uhuoWmJ2WX4plWQ+utE/kBvrJ5TdnKUO4UNgHCB2jY/k4vWM1eNSEQLEZnb7ba/dr70JC5z5BhpRp4NOvsdPu4VKC1WK2MVpGd2jFYNUKDDYY/uNtjQZzdd0KiMTPw+DXVb2B8QY1nYGtzOOZ5ljLJxvcWftY3WdS8v9/Sx9dHM79GNpGTrYBDw9SvG6Me/6vNSqZKcHuF5EtvYW75ac3XnEN4v6pMkrj61uyu0qRDq3gjivfhLK9D2a9xulsvs3eu/aIuDwWWkh78i4oMKYyq2UBh29kl5sc34qOUQhOHwroAc2/e3hLpgghlCdmsLYl7O6KSSSg==^1745041489247; ngetAppId=dZRMlECgRX6QjJnYek1SEhlD2VqSWrchYx670hbEHr_Zs5Ta_69w\u0021-735474581; et_appVIP1=1057115658.17439.0000; _abck=D8B6F63CDAF4608955AFCC122AF2B6F6~0~YAAQNUYDF4M6uCKWAQAA6UCUTA3jgeSu4BDotOr3ZsRjBXQmoU2px82DbpbDI0/dkDd63ZNoNjQRdUJTUMPGMkVVMVCbyfRxyBeh+zqDLb/tA7+uyYC1ywYb3+YD8UryTp3QsnY075P+j0Mc3XLXixM7TmaJegvGRIINZ7DexkV+D8X/xLIZvFW3OdlHDo289+vtRfH0avHAVfcJdVLMy7kveJfYBfkHIZTOisjle0R7M6/rtWJL5oqXJr/vw/zzxENQMR5jD+/ZRZ03wh6YoYC7FSAjz3nYBX42EWQiB9cArHzI9CimVfUgWNNs2EJpZ0+6uJet4QdtJUliA5gIQcK9EZDxJtc65/NV2MDO6QeQ1Bk2BETFT3GfiyVKNA3vEt3cMuGeOrV1TCdr3er1IALOTcXQVZa38+rwVt+TpNU9PHMvnYFvdLQGKbWxquRxsTOh8JV890XiMHSdypS9Ki+WPc+tiPbYiXC62Ry/hpa4xWJVgSMgi592SR2HjdXRHhMFO8U3+TbSltnkO5KFWD8r6jRBNvoPeve/rZpFX2WV8JkQKCaETybiigifmHFhOJ08yHBa3m6HGdw+FjGwzxlPC3ktUT51qg27vdADIqUTK4gR7H/LnTdq6VBD6G8/VKFR3buKjW9Bae6e47CURQ/NjaZyQxJAHpgKwDCYIfuC4vAHQbhy8XO/N7wuFLBoUpwAAzgeBs3KKM0Hke/K+6l1ZW1VGhMIA9p+WL2xMB6OiGOkPVpa56lvF3QoaLnvF0w3AKTjDqEbP9Iw0jheshfi8z3ON+njnLtVWs1dZ7uArOMKH9vbEWitRpNsjLYZarLS9Co51AblwkD37Sn6UApAg10VGVHpAcecSuQnNetGTTbJ+Xk6ijFihxbQZpsTnsQ=~-1~-1~1745043221; bm_sz=1C014777F8FA015BACD38209C2F65F4C~YAAQNUYDF4Q6uCKWAQAA6kCUTBtibbU6jByZaI9wGxMPSbuMeTCdneMwH+FvNzSmV/cKs2kjLdBepudxUZa4maRAuytLZovP+6oln+VTzC4eWAjmiqeliA/dqLopDcY65OXDTQG1gleMkziKb1nPgDtAil4NCjmZewx6l+Aw/jXQ1udlc131rxqIuAmGqUFroOuaKKv82udEEKb7JsvMwreiCUzVxAcuE2g9PgilwDIQZHGWlejHZcQRis8cOWWfDVKvv3UH9JuTz8+0J0b+XbCVEhRIVaAV/H/hebmVxRIWQwOKhCkHW6OtgOgSE9ik2n9U5ZNt8hJHkHiY0hxmPr/GGu3bu24ZfiW6mj7Qh0O5JHX+NymiGhFw6KwzJkPIjdfFG8aZTBXzvD5eUqQYgHWDNdhmqiuNrSAsZWWpsnL4XdqQRU++QSYiBzYFnjSReZxPLI42RYos0iEArj5FJmwfdfUn0w==~4340038~4277825; RT="z=1&dm=www.irctc.co.in&si=ea039a6d-d875-467f-addb-848d12641828&ss=m9nrjeng&sl=5&tt=1lay&bcn=%2F%2F684d0d49.akstat.io%2F&ld=13vjz&nu=9y8m6cy&cl=159hn"; TS018d84e5=01d83d9ce78206a02c312d3e325088361666f560be2ac8f71d3d44dc3efb51c9726d32c3e5f6105be3e1cf7bf5d8a2154746d67548; bm_s=YAAQN0YDF9WoOkeWAQAAD/mUTAOjoUaM9MDp0uS69SUDcZOr/QhpYduXhy4DxYt+I0zzITLV9DPqVwuYwLeQc8bEBh4FqOb/pK6MffoJ0jFr0Qp6xBV3OOq+vF/bvIJ5qe/wRf8gqgAxRieFjGKinySWWk3dd8VKrZGWKipzl8Qgll4inzBNqGaxsbNVSORvOiDRE6EQUnsXOC+b5YDuhiTDQiz7/k622I2qjuVRUSKMN1lJt/2FO3K+yNiPRVLGGDdQ84Dm8/M529Gj6TgmKa8mw0CAIZWxLedzGeuvE0WtwlELsm6ECnHVT/KFYm1Zj7rZmfSVuSWbBT1lDT0Kq6DdX34Ga7wWHtLNY/C6khXpfod9HCpC9moav6TaJqOXVKDYbIZGefHZkbtZP7Ggqi5CT+R6oi4UmPgoX1ML8oRZ4g3uupCnw5bxnEXo729YpbHh3E9oV7bWhnZZr4a2yQ==; _ga_SHTZYKNHG2=GS1.1.1745039630.1.1.1745041565.0.0.0; _ga_NFN218243Z=GS1.1.1745039630.1.1.1745041565.0.0.0; _ga_7K0RMWL72E=GS1.1.1745041477.1.1.1745041565.0.0.0' \
  -H 'greq: GQ:9a2f301b-0467-4bf3-91b9-b0230d6f4179' \
  -H 'origin: https://www.irctc.co.in' \
  -H 'pragma: no-cache' \
  -H 'priority: u=1, i' \
  -H 'referer: https://www.irctc.co.in/nget/booking/train-list' \
  -H 'sec-ch-ua: "Google Chrome";v="135", "Not-A.Brand";v="8", "Chromium";v="135"' \
  -H 'sec-ch-ua-mobile: ?0' \
  -H 'sec-ch-ua-platform: "Windows"' \
  -H 'sec-fetch-dest: empty' \
  -H 'sec-fetch-mode: cors' \
  -H 'sec-fetch-site: same-origin' \
  -H 'spa-csrf-token: 1745041553629--2102340192' \
  -H 'user-agent: Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/135.0.0.0 Safari/537.36' \
  --data-raw '{"paymentFlag":"N","concessionBooking":false,"ftBooking":false,"loyaltyRedemptionBooking":false,"ticketType":"E","quotaCode":"TQ","moreThanOneDay":true,"trainNumber":"13202","fromStnCode":"KYN","toStnCode":"PNBE","isLogedinReq":true,"journeyDate":"20250420","classCode":"SL"}' ;




curl 'https://www.irctc.co.in/eticketing/protected/mapps1/avlFarenquiry/13202/20250420/KYN/PNBE/SL/TQ/N' \
  -H 'greq: GQ:9a2f301b-0467-4bf3-91b9-b0230d6f4179' \
  -H 'sec-ch-ua-platform: "Windows"' \
  -H 'Authorization: Bearer 28ba394c-45f4-4707-a75f-a28c8c2d1692' \
  -H 'bmirak: webbm' \
  -H 'Referer: https://www.irctc.co.in/nget/booking/train-list' \
  -H 'spa-csrf-token: 1745041553629--2102340192' \
  -H 'Accept-Language: en-US,en;q=0.0' \
  -H 'sec-ch-ua: "Google Chrome";v="135", "Not-A.Brand";v="8", "Chromium";v="135"' \
  -H 'bmiyek: BC2382828765A1F05358C89A6038C0FF' \
  -H 'sec-ch-ua-mobile: ?0' \
  -H 'User-Agent: Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/135.0.0.0 Safari/537.36' \
  -H 'Accept: application/json, text/plain, */*' \
  -H 'Content-Type: application/json; charset=UTF-8' \
  -H 'Content-Language: en' \
  --data-raw '{"paymentFlag":"N","concessionBooking":false,"ftBooking":false,"loyaltyRedemptionBooking":false,"ticketType":"E","quotaCode":"TQ","moreThanOneDay":true,"trainNumber":"13202","fromStnCode":"KYN","toStnCode":"PNBE","isLogedinReq":true,"journeyDate":"20250420","classCode":"SL"}' ;




curl 'https://www.google-analytics.com/g/collect?v=2&tid=G-SHTZYKNHG2&gtm=45je54g3v9117897900za200&_p=1745041486402&gcd=13l3l3l3l1l1&npa=0&dma=0&tag_exp=102803279~102813109~102887800~102926062~103027016~103051953~103055465~103077950~103106314~103106316~103116026&cid=1504996631.1745039630&ul=en-us&sr=1536x864&uaa=x86&uab=64&uafvl=Google%2520Chrome%3B135.0.7049.96%7CNot-A.Brand%3B8.0.0.0%7CChromium%3B135.0.7049.96&uamb=0&uam=&uap=Windows&uapv=19.0.0&uaw=0&are=1&frm=0&pscdl=noapi&_eu=AEAAAAI&_s=4&sid=1745039630&sct=1&seg=1&dl=https%3A%2F%2Fwww.irctc.co.in%2Fnget%2Fbooking%2Ftrain-list&dr=https%3A%2F%2Fwww.irctc.co.in%2Fnget%2Ferror&dt=IRCTC%20Next%20Generation%20eTicketing%20System&en=scroll&epn.percent_scrolled=90&_et=40791&tfd=83913' \
  -X 'POST' \
  -H 'sec-ch-ua-platform: "Windows"' \
  -H 'Referer: https://www.irctc.co.in/' \
  -H 'User-Agent: Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/135.0.0.0 Safari/537.36' \
  -H 'sec-ch-ua: "Google Chrome";v="135", "Not-A.Brand";v="8", "Chromium";v="135"' \
  -H 'sec-ch-ua-mobile: ?0' ;




curl 'https://www.google-analytics.com/g/collect?v=2&tid=G-SHTZYKNHG2&gtm=45je54g3v9117897900za200&_p=1745041486402&gcd=13l3l3l3l1l1&npa=0&dma=0&tag_exp=102803279~102813109~102887800~102926062~103027016~103051953~103055465~103077950~103106314~103106316~103116026&cid=1504996631.1745039630&ul=en-us&sr=1536x864&uaa=x86&uab=64&uafvl=Google%2520Chrome%3B135.0.7049.96%7CNot-A.Brand%3B8.0.0.0%7CChromium%3B135.0.7049.96&uamb=0&uam=&uap=Windows&uapv=19.0.0&uaw=0&are=1&frm=0&pscdl=noapi&_eu=AEAAAAI&_s=4&sid=1745039630&sct=1&seg=1&dl=https%3A%2F%2Fwww.irctc.co.in%2Fnget%2Fbooking%2Ftrain-list&dr=https%3A%2F%2Fwww.irctc.co.in%2Fnget%2Ferror&dt=IRCTC%20Next%20Generation%20eTicketing%20System&en=scroll&epn.percent_scrolled=90&_et=40791&tfd=83913' \
  -X 'POST' \
  -H 'accept: */*' \
  -H 'accept-language: en-US,en;q=0.9,de;q=0.8,zh-CN;q=0.7,zh;q=0.6' \
  -H 'cache-control: no-cache' \
  -H 'content-length: 0' \
  -b 'ar_debug=1' \
  -H 'origin: https://www.irctc.co.in' \
  -H 'pragma: no-cache' \
  -H 'priority: u=1, i' \
  -H 'referer: https://www.irctc.co.in/' \
  -H 'sec-ch-ua: "Google Chrome";v="135", "Not-A.Brand";v="8", "Chromium";v="135"' \
  -H 'sec-ch-ua-mobile: ?0' \
  -H 'sec-ch-ua-platform: "Windows"' \
  -H 'sec-fetch-dest: empty' \
  -H 'sec-fetch-mode: no-cors' \
  -H 'sec-fetch-site: cross-site' \
  -H 'sec-fetch-storage-access: active' \
  -H 'user-agent: Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/135.0.0.0 Safari/537.36' ;




curl 'https://www.irctc.co.in/eticketing/protected/mapps1/avlFarenquiry/13202/20250420/KYN/PNBE/3E/TQ/N' \
  -H 'accept: application/json, text/plain, */*' \
  -H 'accept-language: en-US,en;q=0.0' \
  -H 'authorization: Bearer 28ba394c-45f4-4707-a75f-a28c8c2d1692' \
  -H 'bmirak: webbm' \
  -H 'bmiyek: BC2382828765A1F05358C89A6038C0FF' \
  -H 'cache-control: no-cache' \
  -H 'content-language: en' \
  -H 'content-type: application/json; charset=UTF-8' \
  -b $'bm_ss=ab8e18ef4e; _gid=GA1.3.848614353.1745039630; _gcl_au=1.1.62160036.1745041395; _ga_R24JMMNBXX=GS1.1.1745041395.1.0.1745041395.60.0.0; bm_so=BAD45DE45A27169F689873389A1A82BB7952586A65292A3EAE54527244F77F26~YAAQNUYDF1s0uCKWAQAAZ9CTTAOZm709KRc4fkcke198+g+g1PSx8UnGUu+G9fHsf16sbKdiOS7O9kD9krxPsK8I85A9um9Tr+9THtXVK7fRKM/Wa46Ysen1OWZBmKKlF96CGhTHQ+Pjm8Xe6uhuoWmJ2WX4plWQ+utE/kBvrJ5TdnKUO4UNgHCB2jY/k4vWM1eNSEQLEZnb7ba/dr70JC5z5BhpRp4NOvsdPu4VKC1WK2MVpGd2jFYNUKDDYY/uNtjQZzdd0KiMTPw+DXVb2B8QY1nYGtzOOZ5ljLJxvcWftY3WdS8v9/Sx9dHM79GNpGTrYBDw9SvG6Me/6vNSqZKcHuF5EtvYW75ac3XnEN4v6pMkrj61uyu0qRDq3gjivfhLK9D2a9xulsvs3eu/aIuDwWWkh78i4oMKYyq2UBh29kl5sc34qOUQhOHwroAc2/e3hLpgghlCdmsLYl7O6KSSSg==; _ga=GA1.1.1504996631.1745039630; _ga_JSTMKS9Y3J=GS1.1.1745039631.1.1.1745041488.0.0.0; bm_lso=BAD45DE45A27169F689873389A1A82BB7952586A65292A3EAE54527244F77F26~YAAQNUYDF1s0uCKWAQAAZ9CTTAOZm709KRc4fkcke198+g+g1PSx8UnGUu+G9fHsf16sbKdiOS7O9kD9krxPsK8I85A9um9Tr+9THtXVK7fRKM/Wa46Ysen1OWZBmKKlF96CGhTHQ+Pjm8Xe6uhuoWmJ2WX4plWQ+utE/kBvrJ5TdnKUO4UNgHCB2jY/k4vWM1eNSEQLEZnb7ba/dr70JC5z5BhpRp4NOvsdPu4VKC1WK2MVpGd2jFYNUKDDYY/uNtjQZzdd0KiMTPw+DXVb2B8QY1nYGtzOOZ5ljLJxvcWftY3WdS8v9/Sx9dHM79GNpGTrYBDw9SvG6Me/6vNSqZKcHuF5EtvYW75ac3XnEN4v6pMkrj61uyu0qRDq3gjivfhLK9D2a9xulsvs3eu/aIuDwWWkh78i4oMKYyq2UBh29kl5sc34qOUQhOHwroAc2/e3hLpgghlCdmsLYl7O6KSSSg==^1745041489247; ngetAppId=dZRMlECgRX6QjJnYek1SEhlD2VqSWrchYx670hbEHr_Zs5Ta_69w\u0021-735474581; et_appVIP1=1057115658.17439.0000; _abck=D8B6F63CDAF4608955AFCC122AF2B6F6~0~YAAQNUYDF4M6uCKWAQAA6UCUTA3jgeSu4BDotOr3ZsRjBXQmoU2px82DbpbDI0/dkDd63ZNoNjQRdUJTUMPGMkVVMVCbyfRxyBeh+zqDLb/tA7+uyYC1ywYb3+YD8UryTp3QsnY075P+j0Mc3XLXixM7TmaJegvGRIINZ7DexkV+D8X/xLIZvFW3OdlHDo289+vtRfH0avHAVfcJdVLMy7kveJfYBfkHIZTOisjle0R7M6/rtWJL5oqXJr/vw/zzxENQMR5jD+/ZRZ03wh6YoYC7FSAjz3nYBX42EWQiB9cArHzI9CimVfUgWNNs2EJpZ0+6uJet4QdtJUliA5gIQcK9EZDxJtc65/NV2MDO6QeQ1Bk2BETFT3GfiyVKNA3vEt3cMuGeOrV1TCdr3er1IALOTcXQVZa38+rwVt+TpNU9PHMvnYFvdLQGKbWxquRxsTOh8JV890XiMHSdypS9Ki+WPc+tiPbYiXC62Ry/hpa4xWJVgSMgi592SR2HjdXRHhMFO8U3+TbSltnkO5KFWD8r6jRBNvoPeve/rZpFX2WV8JkQKCaETybiigifmHFhOJ08yHBa3m6HGdw+FjGwzxlPC3ktUT51qg27vdADIqUTK4gR7H/LnTdq6VBD6G8/VKFR3buKjW9Bae6e47CURQ/NjaZyQxJAHpgKwDCYIfuC4vAHQbhy8XO/N7wuFLBoUpwAAzgeBs3KKM0Hke/K+6l1ZW1VGhMIA9p+WL2xMB6OiGOkPVpa56lvF3QoaLnvF0w3AKTjDqEbP9Iw0jheshfi8z3ON+njnLtVWs1dZ7uArOMKH9vbEWitRpNsjLYZarLS9Co51AblwkD37Sn6UApAg10VGVHpAcecSuQnNetGTTbJ+Xk6ijFihxbQZpsTnsQ=~-1~-1~1745043221; bm_sz=1C014777F8FA015BACD38209C2F65F4C~YAAQNUYDF4Q6uCKWAQAA6kCUTBtibbU6jByZaI9wGxMPSbuMeTCdneMwH+FvNzSmV/cKs2kjLdBepudxUZa4maRAuytLZovP+6oln+VTzC4eWAjmiqeliA/dqLopDcY65OXDTQG1gleMkziKb1nPgDtAil4NCjmZewx6l+Aw/jXQ1udlc131rxqIuAmGqUFroOuaKKv82udEEKb7JsvMwreiCUzVxAcuE2g9PgilwDIQZHGWlejHZcQRis8cOWWfDVKvv3UH9JuTz8+0J0b+XbCVEhRIVaAV/H/hebmVxRIWQwOKhCkHW6OtgOgSE9ik2n9U5ZNt8hJHkHiY0hxmPr/GGu3bu24ZfiW6mj7Qh0O5JHX+NymiGhFw6KwzJkPIjdfFG8aZTBXzvD5eUqQYgHWDNdhmqiuNrSAsZWWpsnL4XdqQRU++QSYiBzYFnjSReZxPLI42RYos0iEArj5FJmwfdfUn0w==~4340038~4277825; TS018d84e5=01d83d9ce78206a02c312d3e325088361666f560be2ac8f71d3d44dc3efb51c9726d32c3e5f6105be3e1cf7bf5d8a2154746d67548; _ga_SHTZYKNHG2=GS1.1.1745039630.1.1.1745041565.0.0.0; _ga_NFN218243Z=GS1.1.1745039630.1.1.1745041565.0.0.0; _ga_7K0RMWL72E=GS1.1.1745041477.1.1.1745041565.0.0.0; bm_s=YAAQN0YDF5GpOkeWAQAA7BKVTAN5nougaQukyrr4G34bfDfwr4kUVIkwBW+cblgav1p+FLGMpuDvMhYqG7CShL6WYqJPz1S+xX0Mkio+IfOSEz+Drz9M3sQj62cBWR6fP32w1zeluZVtRqb1Kros2GSGF2LD8gx3gd9VgMFweVmVNuNcPdChmndtIcgNvDPJaxAG0LK4HyoxsvrOrEEDzWrzpStRVxn5H2e9CS4Gnkx/c3e7Ogz+VbTlEfZFvFXgzLAInNeKbSYXMlZWUVw0c3gfwZXxHzHPvhHA+tX2tQFkQj12t/wcbhdGVETMqOe5FvsD/Q0X5i5TlP3PqU3LXDsLrwtVbDuBi2hlLL8zguiumyJjKmHE7r1Yio81okf4w3SzTRItfNGlazwEt9BVo40APccAatwoFiauzRuabyOgUhaC/z9erpJtUvcf6QorBFsYBVD10+nCH9/vT/Emvw==; RT="z=1&dm=www.irctc.co.in&si=ea039a6d-d875-467f-addb-848d12641828&ss=m9nrjeng&sl=5&tt=1lay&bcn=%2F%2F684d0d49.akstat.io%2F&ld=13vjz&nu=9y8m6cy&cl=15mkb"' \
  -H 'greq: GQ:9a2f301b-0467-4bf3-91b9-b0230d6f4179' \
  -H 'origin: https://www.irctc.co.in' \
  -H 'pragma: no-cache' \
  -H 'priority: u=1, i' \
  -H 'referer: https://www.irctc.co.in/nget/booking/train-list' \
  -H 'sec-ch-ua: "Google Chrome";v="135", "Not-A.Brand";v="8", "Chromium";v="135"' \
  -H 'sec-ch-ua-mobile: ?0' \
  -H 'sec-ch-ua-platform: "Windows"' \
  -H 'sec-fetch-dest: empty' \
  -H 'sec-fetch-mode: cors' \
  -H 'sec-fetch-site: same-origin' \
  -H 'spa-csrf-token: 1745041560226--1887879189' \
  -H 'user-agent: Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/135.0.0.0 Safari/537.36' \
  --data-raw '{"paymentFlag":"N","concessionBooking":false,"ftBooking":false,"loyaltyRedemptionBooking":false,"ticketType":"E","quotaCode":"TQ","moreThanOneDay":true,"trainNumber":"13202","fromStnCode":"KYN","toStnCode":"PNBE","isLogedinReq":true,"journeyDate":"20250420","classCode":"3E"}' ;




curl 'https://www.irctc.co.in/eticketing/protected/mapps1/avlFarenquiry/13202/20250420/KYN/PNBE/3E/TQ/N' \
  -H 'greq: GQ:9a2f301b-0467-4bf3-91b9-b0230d6f4179' \
  -H 'sec-ch-ua-platform: "Windows"' \
  -H 'Authorization: Bearer 28ba394c-45f4-4707-a75f-a28c8c2d1692' \
  -H 'bmirak: webbm' \
  -H 'Referer: https://www.irctc.co.in/nget/booking/train-list' \
  -H 'spa-csrf-token: 1745041560226--1887879189' \
  -H 'Accept-Language: en-US,en;q=0.0' \
  -H 'sec-ch-ua: "Google Chrome";v="135", "Not-A.Brand";v="8", "Chromium";v="135"' \
  -H 'bmiyek: BC2382828765A1F05358C89A6038C0FF' \
  -H 'sec-ch-ua-mobile: ?0' \
  -H 'User-Agent: Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/135.0.0.0 Safari/537.36' \
  -H 'Accept: application/json, text/plain, */*' \
  -H 'Content-Type: application/json; charset=UTF-8' \
  -H 'Content-Language: en' \
  --data-raw '{"paymentFlag":"N","concessionBooking":false,"ftBooking":false,"loyaltyRedemptionBooking":false,"ticketType":"E","quotaCode":"TQ","moreThanOneDay":true,"trainNumber":"13202","fromStnCode":"KYN","toStnCode":"PNBE","isLogedinReq":true,"journeyDate":"20250420","classCode":"3E"}' ;




curl 'https://www.irctc.co.in/eticketing/protected/mapps1/boardingStationEnq' \
  -H 'accept: application/json, text/plain, */*' \
  -H 'accept-language: en-US,en;q=0.0' \
  -H 'authorization: Bearer 28ba394c-45f4-4707-a75f-a28c8c2d1692' \
  -H 'bmirak: webbm' \
  -H 'bmiyek: BC2382828765A1F05358C89A6038C0FF' \
  -H 'cache-control: no-cache' \
  -H 'content-language: en' \
  -H 'content-type: application/json; charset=UTF-8' \
  -b $'bm_ss=ab8e18ef4e; _gid=GA1.3.848614353.1745039630; _gcl_au=1.1.62160036.1745041395; _ga_R24JMMNBXX=GS1.1.1745041395.1.0.1745041395.60.0.0; bm_so=BAD45DE45A27169F689873389A1A82BB7952586A65292A3EAE54527244F77F26~YAAQNUYDF1s0uCKWAQAAZ9CTTAOZm709KRc4fkcke198+g+g1PSx8UnGUu+G9fHsf16sbKdiOS7O9kD9krxPsK8I85A9um9Tr+9THtXVK7fRKM/Wa46Ysen1OWZBmKKlF96CGhTHQ+Pjm8Xe6uhuoWmJ2WX4plWQ+utE/kBvrJ5TdnKUO4UNgHCB2jY/k4vWM1eNSEQLEZnb7ba/dr70JC5z5BhpRp4NOvsdPu4VKC1WK2MVpGd2jFYNUKDDYY/uNtjQZzdd0KiMTPw+DXVb2B8QY1nYGtzOOZ5ljLJxvcWftY3WdS8v9/Sx9dHM79GNpGTrYBDw9SvG6Me/6vNSqZKcHuF5EtvYW75ac3XnEN4v6pMkrj61uyu0qRDq3gjivfhLK9D2a9xulsvs3eu/aIuDwWWkh78i4oMKYyq2UBh29kl5sc34qOUQhOHwroAc2/e3hLpgghlCdmsLYl7O6KSSSg==; _ga=GA1.1.1504996631.1745039630; _ga_JSTMKS9Y3J=GS1.1.1745039631.1.1.1745041488.0.0.0; bm_lso=BAD45DE45A27169F689873389A1A82BB7952586A65292A3EAE54527244F77F26~YAAQNUYDF1s0uCKWAQAAZ9CTTAOZm709KRc4fkcke198+g+g1PSx8UnGUu+G9fHsf16sbKdiOS7O9kD9krxPsK8I85A9um9Tr+9THtXVK7fRKM/Wa46Ysen1OWZBmKKlF96CGhTHQ+Pjm8Xe6uhuoWmJ2WX4plWQ+utE/kBvrJ5TdnKUO4UNgHCB2jY/k4vWM1eNSEQLEZnb7ba/dr70JC5z5BhpRp4NOvsdPu4VKC1WK2MVpGd2jFYNUKDDYY/uNtjQZzdd0KiMTPw+DXVb2B8QY1nYGtzOOZ5ljLJxvcWftY3WdS8v9/Sx9dHM79GNpGTrYBDw9SvG6Me/6vNSqZKcHuF5EtvYW75ac3XnEN4v6pMkrj61uyu0qRDq3gjivfhLK9D2a9xulsvs3eu/aIuDwWWkh78i4oMKYyq2UBh29kl5sc34qOUQhOHwroAc2/e3hLpgghlCdmsLYl7O6KSSSg==^1745041489247; ngetAppId=dZRMlECgRX6QjJnYek1SEhlD2VqSWrchYx670hbEHr_Zs5Ta_69w\u0021-735474581; et_appVIP1=1057115658.17439.0000; _abck=D8B6F63CDAF4608955AFCC122AF2B6F6~0~YAAQNUYDF4M6uCKWAQAA6UCUTA3jgeSu4BDotOr3ZsRjBXQmoU2px82DbpbDI0/dkDd63ZNoNjQRdUJTUMPGMkVVMVCbyfRxyBeh+zqDLb/tA7+uyYC1ywYb3+YD8UryTp3QsnY075P+j0Mc3XLXixM7TmaJegvGRIINZ7DexkV+D8X/xLIZvFW3OdlHDo289+vtRfH0avHAVfcJdVLMy7kveJfYBfkHIZTOisjle0R7M6/rtWJL5oqXJr/vw/zzxENQMR5jD+/ZRZ03wh6YoYC7FSAjz3nYBX42EWQiB9cArHzI9CimVfUgWNNs2EJpZ0+6uJet4QdtJUliA5gIQcK9EZDxJtc65/NV2MDO6QeQ1Bk2BETFT3GfiyVKNA3vEt3cMuGeOrV1TCdr3er1IALOTcXQVZa38+rwVt+TpNU9PHMvnYFvdLQGKbWxquRxsTOh8JV890XiMHSdypS9Ki+WPc+tiPbYiXC62Ry/hpa4xWJVgSMgi592SR2HjdXRHhMFO8U3+TbSltnkO5KFWD8r6jRBNvoPeve/rZpFX2WV8JkQKCaETybiigifmHFhOJ08yHBa3m6HGdw+FjGwzxlPC3ktUT51qg27vdADIqUTK4gR7H/LnTdq6VBD6G8/VKFR3buKjW9Bae6e47CURQ/NjaZyQxJAHpgKwDCYIfuC4vAHQbhy8XO/N7wuFLBoUpwAAzgeBs3KKM0Hke/K+6l1ZW1VGhMIA9p+WL2xMB6OiGOkPVpa56lvF3QoaLnvF0w3AKTjDqEbP9Iw0jheshfi8z3ON+njnLtVWs1dZ7uArOMKH9vbEWitRpNsjLYZarLS9Co51AblwkD37Sn6UApAg10VGVHpAcecSuQnNetGTTbJ+Xk6ijFihxbQZpsTnsQ=~-1~-1~1745043221; bm_sz=1C014777F8FA015BACD38209C2F65F4C~YAAQNUYDF4Q6uCKWAQAA6kCUTBtibbU6jByZaI9wGxMPSbuMeTCdneMwH+FvNzSmV/cKs2kjLdBepudxUZa4maRAuytLZovP+6oln+VTzC4eWAjmiqeliA/dqLopDcY65OXDTQG1gleMkziKb1nPgDtAil4NCjmZewx6l+Aw/jXQ1udlc131rxqIuAmGqUFroOuaKKv82udEEKb7JsvMwreiCUzVxAcuE2g9PgilwDIQZHGWlejHZcQRis8cOWWfDVKvv3UH9JuTz8+0J0b+XbCVEhRIVaAV/H/hebmVxRIWQwOKhCkHW6OtgOgSE9ik2n9U5ZNt8hJHkHiY0hxmPr/GGu3bu24ZfiW6mj7Qh0O5JHX+NymiGhFw6KwzJkPIjdfFG8aZTBXzvD5eUqQYgHWDNdhmqiuNrSAsZWWpsnL4XdqQRU++QSYiBzYFnjSReZxPLI42RYos0iEArj5FJmwfdfUn0w==~4340038~4277825; TS018d84e5=01d83d9ce78206a02c312d3e325088361666f560be2ac8f71d3d44dc3efb51c9726d32c3e5f6105be3e1cf7bf5d8a2154746d67548; _ga_SHTZYKNHG2=GS1.1.1745039630.1.1.1745041565.0.0.0; _ga_NFN218243Z=GS1.1.1745039630.1.1.1745041565.0.0.0; _ga_7K0RMWL72E=GS1.1.1745041477.1.1.1745041565.0.0.0; RT="z=1&dm=www.irctc.co.in&si=ea039a6d-d875-467f-addb-848d12641828&ss=m9nrjeng&sl=5&tt=1lay&bcn=%2F%2F684d0d49.akstat.io%2F&ld=13vjz&nu=9y8m6cy&cl=15mkb"; bm_s=YAAQN0YDF8upOkeWAQAA5RmVTAPXpsYUmwNnR8QQ+/sonrlAPsrIG6zABEy8N9AuBf8m0RRBzl1Y1NNzCyWFplAwXi3K4B3ap0T6Vsz8EP8b6nt6QeXo4i9q/J9+GL6EgAbLloXlJOOVtVbbQwqZA1dvCdyY+bmMIxqIDvAgCJDHU8+E76BH20oClrACwf9pqH+jF3veP2Fplz/M4DJkb47mJJP5cWyYJKf9hPMnELssWCuueazXn0YSItxCaKkG+aHX2RJ0zUulgLeF9AQLLCUDpSoQpEn6EaYEcOS6U0fVZ1wVVcCQvXVb4k0o6q5ew1n7rT7eVbtvQlL0DDBOmaPv1d/nH2Zhpsh/mB1Zl9Vhfv+QsI0ozE+cnHOpuTgHwBtT1RtMyE9SX3aGLklUhZGZCiYQpsziK06me0UcbGA/3ZTx7xUDd7DHwxVWVY17Ir5vTrnPz+vvFWzLluL31g==' \
  -H 'greq: GQ:9a2f301b-0467-4bf3-91b9-b0230d6f4179' \
  -H 'origin: https://www.irctc.co.in' \
  -H 'pragma: no-cache' \
  -H 'priority: u=1, i' \
  -H 'referer: https://www.irctc.co.in/nget/booking/train-list' \
  -H 'sec-ch-ua: "Google Chrome";v="135", "Not-A.Brand";v="8", "Chromium";v="135"' \
  -H 'sec-ch-ua-mobile: ?0' \
  -H 'sec-ch-ua-platform: "Windows"' \
  -H 'sec-fetch-dest: empty' \
  -H 'sec-fetch-mode: cors' \
  -H 'sec-fetch-site: same-origin' \
  -H 'spa-csrf-token: 1745041562023-1903680508' \
  -H 'user-agent: Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/135.0.0.0 Safari/537.36' \
  --data-raw '{"clusterFlag":"N","onwardFlag":"N","cod":"false","reservationMode":"WS_TA_B2C","autoUpgradationSelected":false,"gnToCkOpted":false,"paymentType":1,"twoPhaseAuthRequired":false,"captureAddress":0,"alternateAvlInputDTO":[{"trainNo":"13202","destStn":"PNBE","srcStn":"KYN","jrnyDate":"20250420","quotaCode":"TQ","jrnyClass":"3E","concessionPassengers":false}],"passBooking":false,"journalistBooking":false}' ;




curl 'https://www.irctc.co.in/eticketing/protected/mapps1/boardingStationEnq' \
  -H 'greq: GQ:9a2f301b-0467-4bf3-91b9-b0230d6f4179' \
  -H 'sec-ch-ua-platform: "Windows"' \
  -H 'Authorization: Bearer 28ba394c-45f4-4707-a75f-a28c8c2d1692' \
  -H 'bmirak: webbm' \
  -H 'Referer: https://www.irctc.co.in/nget/booking/train-list' \
  -H 'spa-csrf-token: 1745041562023-1903680508' \
  -H 'Accept-Language: en-US,en;q=0.0' \
  -H 'sec-ch-ua: "Google Chrome";v="135", "Not-A.Brand";v="8", "Chromium";v="135"' \
  -H 'bmiyek: BC2382828765A1F05358C89A6038C0FF' \
  -H 'sec-ch-ua-mobile: ?0' \
  -H 'User-Agent: Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/135.0.0.0 Safari/537.36' \
  -H 'Accept: application/json, text/plain, */*' \
  -H 'Content-Type: application/json; charset=UTF-8' \
  -H 'Content-Language: en' \
  --data-raw '{"clusterFlag":"N","onwardFlag":"N","cod":"false","reservationMode":"WS_TA_B2C","autoUpgradationSelected":false,"gnToCkOpted":false,"paymentType":1,"twoPhaseAuthRequired":false,"captureAddress":0,"alternateAvlInputDTO":[{"trainNo":"13202","destStn":"PNBE","srcStn":"KYN","jrnyDate":"20250420","quotaCode":"TQ","jrnyClass":"3E","concessionPassengers":false}],"passBooking":false,"journalistBooking":false}' ;




curl 'https://securepubads.g.doubleclick.net/gampad/ads?pvsid=632509865837418&correlator=4002469224131892&eid=95353385%2C31091816%2C95355263%2C83321073%2C31086809%2C31061691%2C31061692&output=ldjh&gdfp_req=1&vrg=202504160101&ptt=17&impl=fifs&iu_parts=37179215%2CGPT_NWEB_PASSENGER_TOP%2CGPT_NWEB_PASSENGER_BOTTOM%2CGPT_NWEB_PASSENGER_RIGHT1&enc_prev_ius=%2F0%2F1%2C%2F0%2F2%2C%2F0%2F3&prev_iu_szs=970x90%2C970x90%7C728x90%2C300x600%7C120x600%7C160x600&ifi=20&didk=3955185294~3955184261~3955203868&dids=div-gpt-ad-509517-0~div-gpt-ad-509518-0~div-gpt-ad-509519-0&adfs=2366464911~2407403557~2275820306&sfv=1-0-41&sc=1&cookie_enabled=1&abxe=1&dt=1745041649415&lmt=1744719295&adxs=-12245933%2C-12245933%2C-12245933&adys=-12245933%2C-12245933%2C-12245933&biw=1203&bih=912&scr_x=0&scr_y=1331&btvi=-1%7C-1%7C-1&ucis=k%7Cl%7Cm&oid=2&u_his=39&u_h=864&u_w=1536&u_ah=816&u_aw=1536&u_cd=24&u_sd=1&u_tz=330&dmc=8&bc=31&nvt=1&uach=WyJXaW5kb3dzIiwiMTkuMC4wIiwieDg2IiwiIiwiMTM1LjAuNzA0OS45NiIsbnVsbCwwLG51bGwsIjY0IixbWyJHb29nbGUgQ2hyb21lIiwiMTM1LjAuNzA0OS45NiJdLFsiTm90LUEuQnJhbmQiLCI4LjAuMC4wIl0sWyJDaHJvbWl1bSIsIjEzNS4wLjcwNDkuOTYiXV0sMF0.&uas=3&url=https%3A%2F%2Fwww.irctc.co.in%2Fnget%2Fbooking%2Fpsgninput&ref=https%3A%2F%2Fwww.irctc.co.in%2Fnget%2Ferror&rumc=632509865837418&rume=1&vis=1&psz=1203x1%7C872x0%7C300x147&msz=0x0%7C0x0%7C0x0&fws=128%2C128%2C128&ohw=0%2C0%2C0&topics=3&tps=3&htps=10&nt=1&psd=WzMxLFtdLG51bGwsM10.&dlt=1745041486247&idt=1661&prev_scp=Destination%3DPNBE%26Quota%3DTQ%26Departure%3D20042025%26Meal%3D0%26Gender%3DM%26TrainType%3DO%26Arrival%3D21042025%26Age%3D66%26Source%3DKYN%26Classes%3D3E%7CDestination%3DPNBE%26Quota%3DTQ%26Departure%3D20042025%26Meal%3D0%26Gender%3DM%26TrainType%3DO%26Arrival%3D21042025%26Age%3D66%26Source%3DKYN%26Classes%3D3E%7CDestination%3DPNBE%26Quota%3DTQ%26Departure%3D20042025%26Meal%3D0%26Gender%3DM%26TrainType%3DO%26Arrival%3D21042025%26Age%3D66%26Source%3DKYN%26Classes%3D3E&adks=4090631086%2C1403516850%2C1057168398&frm=20&eoidce=1&td=1&egid=16524&tan=6156e5d4-379d-4b6e-8367-3ad443808ca3%2C6156e5d4-379d-4b6e-8367-3ad443808ca4%2C6156e5d4-379d-4b6e-8367-3ad443808ca5&tdf=2' \
  -H 'sec-ch-ua-platform: "Windows"' \
  -H 'Referer: https://www.irctc.co.in/' \
  -H 'User-Agent: Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/135.0.0.0 Safari/537.36' \
  -H 'Accept: */*' \
  -H 'sec-ch-ua: "Google Chrome";v="135", "Not-A.Brand";v="8", "Chromium";v="135"' \
  -H 'sec-ch-ua-mobile: ?0' ;




curl 'https://securepubads.g.doubleclick.net/gampad/ads?pvsid=632509865837418&correlator=4002469224131892&eid=95353385%2C31091816%2C95355263%2C83321073%2C31086809%2C31061691%2C31061692&output=ldjh&gdfp_req=1&vrg=202504160101&ptt=17&impl=fifs&iu_parts=37179215%2CGPT_NWEB_PASSENGER_TOP%2CGPT_NWEB_PASSENGER_BOTTOM%2CGPT_NWEB_PASSENGER_RIGHT1&enc_prev_ius=%2F0%2F1%2C%2F0%2F2%2C%2F0%2F3&prev_iu_szs=970x90%2C970x90%7C728x90%2C300x600%7C120x600%7C160x600&ifi=20&didk=3955185294~3955184261~3955203868&dids=div-gpt-ad-509517-0~div-gpt-ad-509518-0~div-gpt-ad-509519-0&adfs=2366464911~2407403557~2275820306&sfv=1-0-41&sc=1&cookie_enabled=1&abxe=1&dt=1745041649415&lmt=1744719295&adxs=-12245933%2C-12245933%2C-12245933&adys=-12245933%2C-12245933%2C-12245933&biw=1203&bih=912&scr_x=0&scr_y=1331&btvi=-1%7C-1%7C-1&ucis=k%7Cl%7Cm&oid=2&u_his=39&u_h=864&u_w=1536&u_ah=816&u_aw=1536&u_cd=24&u_sd=1&u_tz=330&dmc=8&bc=31&nvt=1&uach=WyJXaW5kb3dzIiwiMTkuMC4wIiwieDg2IiwiIiwiMTM1LjAuNzA0OS45NiIsbnVsbCwwLG51bGwsIjY0IixbWyJHb29nbGUgQ2hyb21lIiwiMTM1LjAuNzA0OS45NiJdLFsiTm90LUEuQnJhbmQiLCI4LjAuMC4wIl0sWyJDaHJvbWl1bSIsIjEzNS4wLjcwNDkuOTYiXV0sMF0.&uas=3&url=https%3A%2F%2Fwww.irctc.co.in%2Fnget%2Fbooking%2Fpsgninput&ref=https%3A%2F%2Fwww.irctc.co.in%2Fnget%2Ferror&rumc=632509865837418&rume=1&vis=1&psz=1203x1%7C872x0%7C300x147&msz=0x0%7C0x0%7C0x0&fws=128%2C128%2C128&ohw=0%2C0%2C0&topics=3&tps=3&htps=10&nt=1&psd=WzMxLFtdLG51bGwsM10.&dlt=1745041486247&idt=1661&prev_scp=Destination%3DPNBE%26Quota%3DTQ%26Departure%3D20042025%26Meal%3D0%26Gender%3DM%26TrainType%3DO%26Arrival%3D21042025%26Age%3D66%26Source%3DKYN%26Classes%3D3E%7CDestination%3DPNBE%26Quota%3DTQ%26Departure%3D20042025%26Meal%3D0%26Gender%3DM%26TrainType%3DO%26Arrival%3D21042025%26Age%3D66%26Source%3DKYN%26Classes%3D3E%7CDestination%3DPNBE%26Quota%3DTQ%26Departure%3D20042025%26Meal%3D0%26Gender%3DM%26TrainType%3DO%26Arrival%3D21042025%26Age%3D66%26Source%3DKYN%26Classes%3D3E&adks=4090631086%2C1403516850%2C1057168398&frm=20&eoidce=1&td=1&egid=16524&tan=6156e5d4-379d-4b6e-8367-3ad443808ca3%2C6156e5d4-379d-4b6e-8367-3ad443808ca4%2C6156e5d4-379d-4b6e-8367-3ad443808ca5&tdf=2' \
  -H 'sec-ch-ua-platform: "Windows"' \
  -H 'Referer: https://www.irctc.co.in/' \
  -H 'User-Agent: Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/135.0.0.0 Safari/537.36' \
  -H 'sec-ch-ua: "Google Chrome";v="135", "Not-A.Brand";v="8", "Chromium";v="135"' \
  -H 'sec-ch-ua-mobile: ?0' ;




curl 'https://www.google-analytics.com/g/collect?v=2&tid=G-NFN218243Z&gtm=45je54g3v872522363za200zb9117897900&_p=1745041486402&gcd=13l3l3l3l1l1&npa=0&dma=0&tag_exp=102803279~102813109~102887800~102926062~103027016~103051953~103055465~103077950~103106314~103106316&cid=1504996631.1745039630&ul=en-us&sr=1536x864&uaa=x86&uab=64&uafvl=Google%2520Chrome%3B135.0.7049.96%7CNot-A.Brand%3B8.0.0.0%7CChromium%3B135.0.7049.96&uamb=0&uam=&uap=Windows&uapv=19.0.0&uaw=0&are=1&frm=0&pscdl=noapi&_eu=AEAAAAI&_s=6&dl=https%3A%2F%2Fwww.irctc.co.in%2Fnget%2Fbooking%2Fpsgninput&dr=https%3A%2F%2Fwww.irctc.co.in%2Fnget%2Fbooking%2Ftrain-list&sid=1745039630&sct=1&seg=1&dt=IRCTC%20Next%20Generation%20eTicketing%20System&en=page_view&_et=13323&tfd=170124' \
  -X 'POST' \
  -H 'accept: */*' \
  -H 'accept-language: en-US,en;q=0.9,de;q=0.8,zh-CN;q=0.7,zh;q=0.6' \
  -H 'cache-control: no-cache' \
  -H 'content-length: 0' \
  -b 'ar_debug=1' \
  -H 'origin: https://www.irctc.co.in' \
  -H 'pragma: no-cache' \
  -H 'priority: u=1, i' \
  -H 'referer: https://www.irctc.co.in/' \
  -H 'sec-ch-ua: "Google Chrome";v="135", "Not-A.Brand";v="8", "Chromium";v="135"' \
  -H 'sec-ch-ua-mobile: ?0' \
  -H 'sec-ch-ua-platform: "Windows"' \
  -H 'sec-fetch-dest: empty' \
  -H 'sec-fetch-mode: no-cors' \
  -H 'sec-fetch-site: cross-site' \
  -H 'sec-fetch-storage-access: active' \
  -H 'user-agent: Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/135.0.0.0 Safari/537.36' ;




curl 'https://www.google-analytics.com/g/collect?v=2&tid=G-NFN218243Z&gtm=45je54g3v872522363za200zb9117897900&_p=1745041486402&gcd=13l3l3l3l1l1&npa=0&dma=0&tag_exp=102803279~102813109~102887800~102926062~103027016~103051953~103055465~103077950~103106314~103106316&cid=1504996631.1745039630&ul=en-us&sr=1536x864&uaa=x86&uab=64&uafvl=Google%2520Chrome%3B135.0.7049.96%7CNot-A.Brand%3B8.0.0.0%7CChromium%3B135.0.7049.96&uamb=0&uam=&uap=Windows&uapv=19.0.0&uaw=0&are=1&frm=0&pscdl=noapi&_eu=AEAAAAI&_s=6&dl=https%3A%2F%2Fwww.irctc.co.in%2Fnget%2Fbooking%2Fpsgninput&dr=https%3A%2F%2Fwww.irctc.co.in%2Fnget%2Fbooking%2Ftrain-list&sid=1745039630&sct=1&seg=1&dt=IRCTC%20Next%20Generation%20eTicketing%20System&en=page_view&_et=13323&tfd=170124' \
  -X 'POST' \
  -H 'sec-ch-ua-platform: "Windows"' \
  -H 'Referer: https://www.irctc.co.in/' \
  -H 'User-Agent: Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/135.0.0.0 Safari/537.36' \
  -H 'sec-ch-ua: "Google Chrome";v="135", "Not-A.Brand";v="8", "Chromium";v="135"' \
  -H 'sec-ch-ua-mobile: ?0' ;




curl 'https://www.google-analytics.com/g/collect?v=2&tid=G-7K0RMWL72E&gtm=45je54g3v9116751228za200&_p=1745041486402&gcd=13l3l3l3l1l1&npa=0&dma=0&tag_exp=102803279~102813109~102887800~102926062~103027016~103051953~103055465~103077950~103106314~103106316&cid=1504996631.1745039630&ul=en-us&sr=1536x864&uaa=x86&uab=64&uafvl=Google%2520Chrome%3B135.0.7049.96%7CNot-A.Brand%3B8.0.0.0%7CChromium%3B135.0.7049.96&uamb=0&uam=&uap=Windows&uapv=19.0.0&uaw=0&are=1&frm=0&pscdl=noapi&_eu=AEAIAAI&_s=7&dl=https%3A%2F%2Fwww.irctc.co.in%2Fnget%2Fbooking%2Fpsgninput&dr=https%3A%2F%2Fwww.irctc.co.in%2Fnget%2Fbooking%2Ftrain-list&sid=1745041477&sct=1&seg=1&dt=IRCTC%20Next%20Generation%20eTicketing%20System&en=page_view&_et=13330&tfd=170126' \
  -X 'POST' \
  -H 'accept: */*' \
  -H 'accept-language: en-US,en;q=0.9,de;q=0.8,zh-CN;q=0.7,zh;q=0.6' \
  -H 'cache-control: no-cache' \
  -H 'content-length: 0' \
  -b 'ar_debug=1' \
  -H 'origin: https://www.irctc.co.in' \
  -H 'pragma: no-cache' \
  -H 'priority: u=1, i' \
  -H 'referer: https://www.irctc.co.in/' \
  -H 'sec-ch-ua: "Google Chrome";v="135", "Not-A.Brand";v="8", "Chromium";v="135"' \
  -H 'sec-ch-ua-mobile: ?0' \
  -H 'sec-ch-ua-platform: "Windows"' \
  -H 'sec-fetch-dest: empty' \
  -H 'sec-fetch-mode: no-cors' \
  -H 'sec-fetch-site: cross-site' \
  -H 'sec-fetch-storage-access: active' \
  -H 'user-agent: Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/135.0.0.0 Safari/537.36' ;




curl 'https://www.google-analytics.com/g/collect?v=2&tid=G-7K0RMWL72E&gtm=45je54g3v9116751228za200&_p=1745041486402&gcd=13l3l3l3l1l1&npa=0&dma=0&tag_exp=102803279~102813109~102887800~102926062~103027016~103051953~103055465~103077950~103106314~103106316&cid=1504996631.1745039630&ul=en-us&sr=1536x864&uaa=x86&uab=64&uafvl=Google%2520Chrome%3B135.0.7049.96%7CNot-A.Brand%3B8.0.0.0%7CChromium%3B135.0.7049.96&uamb=0&uam=&uap=Windows&uapv=19.0.0&uaw=0&are=1&frm=0&pscdl=noapi&_eu=AEAIAAI&_s=7&dl=https%3A%2F%2Fwww.irctc.co.in%2Fnget%2Fbooking%2Fpsgninput&dr=https%3A%2F%2Fwww.irctc.co.in%2Fnget%2Fbooking%2Ftrain-list&sid=1745041477&sct=1&seg=1&dt=IRCTC%20Next%20Generation%20eTicketing%20System&en=page_view&_et=13330&tfd=170126' \
  -X 'POST' \
  -H 'sec-ch-ua-platform: "Windows"' \
  -H 'Referer: https://www.irctc.co.in/' \
  -H 'User-Agent: Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/135.0.0.0 Safari/537.36' \
  -H 'sec-ch-ua: "Google Chrome";v="135", "Not-A.Brand";v="8", "Chromium";v="135"' \
  -H 'sec-ch-ua-mobile: ?0' ;




curl 'https://www.irctc.co.in/eticketing/protected/mapps1/allLapAvlFareEnq/Y' \
  -H 'accept: application/json, text/plain, */*' \
  -H 'accept-language: en-US,en;q=0.0' \
  -H 'authorization: Bearer 28ba394c-45f4-4707-a75f-a28c8c2d1692' \
  -H 'bmirak: webbm' \
  -H 'bmiyek: BC2382828765A1F05358C89A6038C0FF' \
  -H 'cache-control: no-cache' \
  -H 'content-language: en' \
  -H 'content-type: application/json; charset=UTF-8' \
  -b $'bm_ss=ab8e18ef4e; _gid=GA1.3.848614353.1745039630; _gcl_au=1.1.62160036.1745041395; _ga_R24JMMNBXX=GS1.1.1745041395.1.0.1745041395.60.0.0; bm_so=BAD45DE45A27169F689873389A1A82BB7952586A65292A3EAE54527244F77F26~YAAQNUYDF1s0uCKWAQAAZ9CTTAOZm709KRc4fkcke198+g+g1PSx8UnGUu+G9fHsf16sbKdiOS7O9kD9krxPsK8I85A9um9Tr+9THtXVK7fRKM/Wa46Ysen1OWZBmKKlF96CGhTHQ+Pjm8Xe6uhuoWmJ2WX4plWQ+utE/kBvrJ5TdnKUO4UNgHCB2jY/k4vWM1eNSEQLEZnb7ba/dr70JC5z5BhpRp4NOvsdPu4VKC1WK2MVpGd2jFYNUKDDYY/uNtjQZzdd0KiMTPw+DXVb2B8QY1nYGtzOOZ5ljLJxvcWftY3WdS8v9/Sx9dHM79GNpGTrYBDw9SvG6Me/6vNSqZKcHuF5EtvYW75ac3XnEN4v6pMkrj61uyu0qRDq3gjivfhLK9D2a9xulsvs3eu/aIuDwWWkh78i4oMKYyq2UBh29kl5sc34qOUQhOHwroAc2/e3hLpgghlCdmsLYl7O6KSSSg==; _ga=GA1.1.1504996631.1745039630; _ga_JSTMKS9Y3J=GS1.1.1745039631.1.1.1745041488.0.0.0; bm_lso=BAD45DE45A27169F689873389A1A82BB7952586A65292A3EAE54527244F77F26~YAAQNUYDF1s0uCKWAQAAZ9CTTAOZm709KRc4fkcke198+g+g1PSx8UnGUu+G9fHsf16sbKdiOS7O9kD9krxPsK8I85A9um9Tr+9THtXVK7fRKM/Wa46Ysen1OWZBmKKlF96CGhTHQ+Pjm8Xe6uhuoWmJ2WX4plWQ+utE/kBvrJ5TdnKUO4UNgHCB2jY/k4vWM1eNSEQLEZnb7ba/dr70JC5z5BhpRp4NOvsdPu4VKC1WK2MVpGd2jFYNUKDDYY/uNtjQZzdd0KiMTPw+DXVb2B8QY1nYGtzOOZ5ljLJxvcWftY3WdS8v9/Sx9dHM79GNpGTrYBDw9SvG6Me/6vNSqZKcHuF5EtvYW75ac3XnEN4v6pMkrj61uyu0qRDq3gjivfhLK9D2a9xulsvs3eu/aIuDwWWkh78i4oMKYyq2UBh29kl5sc34qOUQhOHwroAc2/e3hLpgghlCdmsLYl7O6KSSSg==^1745041489247; ngetAppId=dZRMlECgRX6QjJnYek1SEhlD2VqSWrchYx670hbEHr_Zs5Ta_69w\u0021-735474581; et_appVIP1=1057115658.17439.0000; _abck=D8B6F63CDAF4608955AFCC122AF2B6F6~0~YAAQNUYDF4M6uCKWAQAA6UCUTA3jgeSu4BDotOr3ZsRjBXQmoU2px82DbpbDI0/dkDd63ZNoNjQRdUJTUMPGMkVVMVCbyfRxyBeh+zqDLb/tA7+uyYC1ywYb3+YD8UryTp3QsnY075P+j0Mc3XLXixM7TmaJegvGRIINZ7DexkV+D8X/xLIZvFW3OdlHDo289+vtRfH0avHAVfcJdVLMy7kveJfYBfkHIZTOisjle0R7M6/rtWJL5oqXJr/vw/zzxENQMR5jD+/ZRZ03wh6YoYC7FSAjz3nYBX42EWQiB9cArHzI9CimVfUgWNNs2EJpZ0+6uJet4QdtJUliA5gIQcK9EZDxJtc65/NV2MDO6QeQ1Bk2BETFT3GfiyVKNA3vEt3cMuGeOrV1TCdr3er1IALOTcXQVZa38+rwVt+TpNU9PHMvnYFvdLQGKbWxquRxsTOh8JV890XiMHSdypS9Ki+WPc+tiPbYiXC62Ry/hpa4xWJVgSMgi592SR2HjdXRHhMFO8U3+TbSltnkO5KFWD8r6jRBNvoPeve/rZpFX2WV8JkQKCaETybiigifmHFhOJ08yHBa3m6HGdw+FjGwzxlPC3ktUT51qg27vdADIqUTK4gR7H/LnTdq6VBD6G8/VKFR3buKjW9Bae6e47CURQ/NjaZyQxJAHpgKwDCYIfuC4vAHQbhy8XO/N7wuFLBoUpwAAzgeBs3KKM0Hke/K+6l1ZW1VGhMIA9p+WL2xMB6OiGOkPVpa56lvF3QoaLnvF0w3AKTjDqEbP9Iw0jheshfi8z3ON+njnLtVWs1dZ7uArOMKH9vbEWitRpNsjLYZarLS9Co51AblwkD37Sn6UApAg10VGVHpAcecSuQnNetGTTbJ+Xk6ijFihxbQZpsTnsQ=~-1~-1~1745043221; bm_sz=1C014777F8FA015BACD38209C2F65F4C~YAAQNUYDF4Q6uCKWAQAA6kCUTBtibbU6jByZaI9wGxMPSbuMeTCdneMwH+FvNzSmV/cKs2kjLdBepudxUZa4maRAuytLZovP+6oln+VTzC4eWAjmiqeliA/dqLopDcY65OXDTQG1gleMkziKb1nPgDtAil4NCjmZewx6l+Aw/jXQ1udlc131rxqIuAmGqUFroOuaKKv82udEEKb7JsvMwreiCUzVxAcuE2g9PgilwDIQZHGWlejHZcQRis8cOWWfDVKvv3UH9JuTz8+0J0b+XbCVEhRIVaAV/H/hebmVxRIWQwOKhCkHW6OtgOgSE9ik2n9U5ZNt8hJHkHiY0hxmPr/GGu3bu24ZfiW6mj7Qh0O5JHX+NymiGhFw6KwzJkPIjdfFG8aZTBXzvD5eUqQYgHWDNdhmqiuNrSAsZWWpsnL4XdqQRU++QSYiBzYFnjSReZxPLI42RYos0iEArj5FJmwfdfUn0w==~4340038~4277825; TS018d84e5=01d83d9ce78206a02c312d3e325088361666f560be2ac8f71d3d44dc3efb51c9726d32c3e5f6105be3e1cf7bf5d8a2154746d67548; _ga_SHTZYKNHG2=GS1.1.1745039630.1.1.1745041565.0.0.0; bm_s=YAAQN0YDF8upOkeWAQAA5RmVTAPXpsYUmwNnR8QQ+/sonrlAPsrIG6zABEy8N9AuBf8m0RRBzl1Y1NNzCyWFplAwXi3K4B3ap0T6Vsz8EP8b6nt6QeXo4i9q/J9+GL6EgAbLloXlJOOVtVbbQwqZA1dvCdyY+bmMIxqIDvAgCJDHU8+E76BH20oClrACwf9pqH+jF3veP2Fplz/M4DJkb47mJJP5cWyYJKf9hPMnELssWCuueazXn0YSItxCaKkG+aHX2RJ0zUulgLeF9AQLLCUDpSoQpEn6EaYEcOS6U0fVZ1wVVcCQvXVb4k0o6q5ew1n7rT7eVbtvQlL0DDBOmaPv1d/nH2Zhpsh/mB1Zl9Vhfv+QsI0ozE+cnHOpuTgHwBtT1RtMyE9SX3aGLklUhZGZCiYQpsziK06me0UcbGA/3ZTx7xUDd7DHwxVWVY17Ir5vTrnPz+vvFWzLluL31g==; _ga_NFN218243Z=GS1.1.1745039630.1.1.1745041650.0.0.0; _ga_7K0RMWL72E=GS1.1.1745041477.1.1.1745041650.0.0.0; RT="z=1&dm=www.irctc.co.in&si=ea039a6d-d875-467f-addb-848d12641828&ss=m9nrjeng&sl=5&tt=1lay&bcn=%2F%2F684d0d49.akstat.io%2F&ld=13vjz&nu=9y8m6cy&cl=17qzq"' \
  -H 'greq: GQ:9a2f301b-0467-4bf3-91b9-b0230d6f4179' \
  -H 'origin: https://www.irctc.co.in' \
  -H 'pragma: no-cache' \
  -H 'priority: u=1, i' \
  -H 'referer: https://www.irctc.co.in/nget/booking/psgninput' \
  -H 'sec-ch-ua: "Google Chrome";v="135", "Not-A.Brand";v="8", "Chromium";v="135"' \
  -H 'sec-ch-ua-mobile: ?0' \
  -H 'sec-ch-ua-platform: "Windows"' \
  -H 'sec-fetch-dest: empty' \
  -H 'sec-fetch-mode: cors' \
  -H 'sec-fetch-site: same-origin' \
  -H 'spa-csrf-token: 1745041640674--1567478663' \
  -H 'user-agent: Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/135.0.0.0 Safari/537.36' \
  --data-raw '{"clusterFlag":"N","onwardFlag":"N","cod":"false","reservationMode":"WS_TA_B2C","autoUpgradationSelected":true,"gnToCkOpted":false,"paymentType":"3","twoPhaseAuthRequired":false,"captureAddress":0,"wsUserLogin":"nkd4854","moreThanOneDay":false,"clientTransactionId":"m9nsqq1e","boardingStation":"KYN","reservationUptoStation":"PNBE","mobileNumber":"9015895055","ticketType":"E","mainJourneyTxnId":null,"mainJourneyPnr":"","captcha":"","generalistChildConfirm":false,"ftBooking":false,"loyaltyRedemptionBooking":false,"loyaltyBankId":null,"loyaltyNumber":null,"nosbBooking":false,"warrentType":0,"ftTnCAgree":false,"bookingChoice":1,"bookingConfirmChoice":1,"bookOnlyIfCnf":false,"returnJourney":null,"connectingJourney":false,"lapAvlRequestDTO":[{"trainNo":"13202","journeyDate":"20250420","fromStation":"KYN","toStation":"PNBE","journeyClass":"3E","quota":"TQ","coachId":null,"reservationChoice":"99","ignoreChoiceIfWl":true,"travelInsuranceOpted":false,"warrentType":0,"coachPreferred":false,"autoUpgradation":false,"bookOnlyIfCnf":false,"addMealInput":null,"concessionBooking":false,"passengerList":[{"passengerName":"BHAGYESH DAS","passengerAge":26,"passengerGender":"M","passengerBerthChoice":"","passengerFoodChoice":null,"passengerBedrollChoice":null,"passengerNationality":"IN","passengerCardTypeMaster":null,"passengerCardNumberMaster":null,"psgnConcType":null,"psgnConcCardId":null,"psgnConcDOB":null,"psgnConcCardExpiryDate":null,"psgnConcDOBP":null,"softMemberId":null,"softMemberFlag":null,"psgnConcCardExpiryDateP":null,"passengerVerified":false,"masterPsgnId":null,"mpMemberFlag":null,"passengerForceNumber":null,"passConcessionType":"0","passUPN":null,"passBookingCode":null,"passengerSerialNumber":1,"childBerthFlag":true,"passengerCardType":"NULL_IDCARD","passengerIcardFlag":false,"passengerCardNumber":null},{"passengerName":"BIPIN DAS","passengerAge":60,"passengerGender":"M","passengerBerthChoice":"","passengerFoodChoice":null,"passengerSrCtznConcession":"0","passengerBedrollChoice":null,"passengerNationality":"IN","passengerCardTypeMaster":null,"passengerCardNumberMaster":null,"psgnConcType":null,"psgnConcCardId":null,"psgnConcDOB":null,"psgnConcCardExpiryDate":null,"psgnConcDOBP":null,"softMemberId":null,"softMemberFlag":null,"psgnConcCardExpiryDateP":null,"passengerVerified":false,"masterPsgnId":null,"mpMemberFlag":null,"passengerForceNumber":null,"passConcessionType":"0","passUPN":null,"passBookingCode":null,"passengerSerialNumber":2,"childBerthFlag":true,"passengerCardType":"NULL_IDCARD","passengerIcardFlag":false,"passengerCardNumber":null}],"ssQuotaSplitCoach":"N"}],"gstDetails":{"gstIn":"","error":null}}' ;




curl 'https://www.irctc.co.in/eticketing/protected/mapps1/allLapAvlFareEnq/Y' \
  -H 'greq: GQ:9a2f301b-0467-4bf3-91b9-b0230d6f4179' \
  -H 'sec-ch-ua-platform: "Windows"' \
  -H 'Authorization: Bearer 28ba394c-45f4-4707-a75f-a28c8c2d1692' \
  -H 'bmirak: webbm' \
  -H 'Referer: https://www.irctc.co.in/nget/booking/psgninput' \
  -H 'spa-csrf-token: 1745041640674--1567478663' \
  -H 'Accept-Language: en-US,en;q=0.0' \
  -H 'sec-ch-ua: "Google Chrome";v="135", "Not-A.Brand";v="8", "Chromium";v="135"' \
  -H 'bmiyek: BC2382828765A1F05358C89A6038C0FF' \
  -H 'sec-ch-ua-mobile: ?0' \
  -H 'User-Agent: Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/135.0.0.0 Safari/537.36' \
  -H 'Accept: application/json, text/plain, */*' \
  -H 'Content-Type: application/json; charset=UTF-8' \
  -H 'Content-Language: en' \
  --data-raw '{"clusterFlag":"N","onwardFlag":"N","cod":"false","reservationMode":"WS_TA_B2C","autoUpgradationSelected":true,"gnToCkOpted":false,"paymentType":"3","twoPhaseAuthRequired":false,"captureAddress":0,"wsUserLogin":"nkd4854","moreThanOneDay":false,"clientTransactionId":"m9nsqq1e","boardingStation":"KYN","reservationUptoStation":"PNBE","mobileNumber":"9015895055","ticketType":"E","mainJourneyTxnId":null,"mainJourneyPnr":"","captcha":"","generalistChildConfirm":false,"ftBooking":false,"loyaltyRedemptionBooking":false,"loyaltyBankId":null,"loyaltyNumber":null,"nosbBooking":false,"warrentType":0,"ftTnCAgree":false,"bookingChoice":1,"bookingConfirmChoice":1,"bookOnlyIfCnf":false,"returnJourney":null,"connectingJourney":false,"lapAvlRequestDTO":[{"trainNo":"13202","journeyDate":"20250420","fromStation":"KYN","toStation":"PNBE","journeyClass":"3E","quota":"TQ","coachId":null,"reservationChoice":"99","ignoreChoiceIfWl":true,"travelInsuranceOpted":false,"warrentType":0,"coachPreferred":false,"autoUpgradation":false,"bookOnlyIfCnf":false,"addMealInput":null,"concessionBooking":false,"passengerList":[{"passengerName":"BHAGYESH DAS","passengerAge":26,"passengerGender":"M","passengerBerthChoice":"","passengerFoodChoice":null,"passengerBedrollChoice":null,"passengerNationality":"IN","passengerCardTypeMaster":null,"passengerCardNumberMaster":null,"psgnConcType":null,"psgnConcCardId":null,"psgnConcDOB":null,"psgnConcCardExpiryDate":null,"psgnConcDOBP":null,"softMemberId":null,"softMemberFlag":null,"psgnConcCardExpiryDateP":null,"passengerVerified":false,"masterPsgnId":null,"mpMemberFlag":null,"passengerForceNumber":null,"passConcessionType":"0","passUPN":null,"passBookingCode":null,"passengerSerialNumber":1,"childBerthFlag":true,"passengerCardType":"NULL_IDCARD","passengerIcardFlag":false,"passengerCardNumber":null},{"passengerName":"BIPIN DAS","passengerAge":60,"passengerGender":"M","passengerBerthChoice":"","passengerFoodChoice":null,"passengerSrCtznConcession":"0","passengerBedrollChoice":null,"passengerNationality":"IN","passengerCardTypeMaster":null,"passengerCardNumberMaster":null,"psgnConcType":null,"psgnConcCardId":null,"psgnConcDOB":null,"psgnConcCardExpiryDate":null,"psgnConcDOBP":null,"softMemberId":null,"softMemberFlag":null,"psgnConcCardExpiryDateP":null,"passengerVerified":false,"masterPsgnId":null,"mpMemberFlag":null,"passengerForceNumber":null,"passConcessionType":"0","passUPN":null,"passBookingCode":null,"passengerSerialNumber":2,"childBerthFlag":true,"passengerCardType":"NULL_IDCARD","passengerIcardFlag":false,"passengerCardNumber":null}],"ssQuotaSplitCoach":"N"}],"gstDetails":{"gstIn":"","error":null}}' ;




curl 'https://securepubads.g.doubleclick.net/gampad/ads?pvsid=632509865837418&correlator=3138997595635122&eid=95353385%2C31091816%2C95355263%2C83321073%2C31086809%2C31061691%2C31061692&output=ldjh&gdfp_req=1&vrg=202504160101&ptt=17&impl=fifs&iu_parts=37179215%2CGPT_IRCTC_PASSENGER_DETAIL_CAPTCHA_300X250%2CGPT_NWEB_REVIEW_BOOKING_TOP%2CGPT_NWEB_REVIEW_BOOKING_BOTTOM%2CGPT_NWEB_REVIEW_BOOKING_RIGHT&enc_prev_ius=%2F0%2F1%2C%2F0%2F2%2C%2F0%2F3%2C%2F0%2F4&prev_iu_szs=300x250%2C970x90%2C728x90%2C300x600%7C300x250%7C160x600%7C120x600&ifi=23&didk=3351422080~3952156613~3952155596~3952178929&dids=div-gpt-ad-1658133440721-0~div-gpt-ad-509520-0~div-gpt-ad-509521-0~div-gpt-ad-509522-0&adfs=2094388751~1281992877~1317729197~1075613749&sfv=1-0-41&sc=1&cookie_enabled=1&abxe=1&dt=1745041687257&lmt=1744719295&adxs=-12245933%2C-12245933%2C-12245933%2C-12245933&adys=-12245933%2C-12245933%2C-12245933%2C-12245933&biw=1203&bih=912&scr_x=0&scr_y=577&btvi=-1%7C-1%7C-1%7C-1&ucis=n%7Co%7Cp%7Cq&oid=2&u_his=40&u_h=864&u_w=1536&u_ah=816&u_aw=1536&u_cd=24&u_sd=1&u_tz=330&dmc=8&bc=31&nvt=1&uach=WyJXaW5kb3dzIiwiMTkuMC4wIiwieDg2IiwiIiwiMTM1LjAuNzA0OS45NiIsbnVsbCwwLG51bGwsIjY0IixbWyJHb29nbGUgQ2hyb21lIiwiMTM1LjAuNzA0OS45NiJdLFsiTm90LUEuQnJhbmQiLCI4LjAuMC4wIl0sWyJDaHJvbWl1bSIsIjEzNS4wLjcwNDkuOTYiXV0sMF0.&uas=3&url=https%3A%2F%2Fwww.irctc.co.in%2Fnget%2Fbooking%2FreviewBooking&ref=https%3A%2F%2Fwww.irctc.co.in%2Fnget%2Ferror&rumc=632509865837418&rume=1&vis=1&psz=300x92%7C1203x90%7C872x35%7C300x196&msz=0x0%7C0x0%7C0x0%7C0x0&fws=128%2C128%2C128%2C128&ohw=0%2C0%2C0%2C0&topics=3&tps=3&htps=10&nt=1&psd=WzMxLFtdLG51bGwsM10.&dlt=1745041486247&idt=1661&prev_scp=%7CDestination%3DPNBE%26Quota%3DTQ%26Departure%3D20042025%26Meal%3D0%26Gender%3DM%26TrainType%3DO%26Arrival%3D21042025%26Age%3D66%26Source%3DKYN%26Classes%3D3E%7CDestination%3DPNBE%26Quota%3DTQ%26Departure%3D20042025%26Meal%3D0%26Gender%3DM%26TrainType%3DO%26Arrival%3D21042025%26Age%3D66%26Source%3DKYN%26Classes%3D3E%7CDestination%3DPNBE%26Quota%3DTQ%26Departure%3D20042025%26Meal%3D0%26Gender%3DM%26TrainType%3DO%26Arrival%3D21042025%26Age%3D66%26Source%3DKYN%26Classes%3D3E&adks=607550432%2C2470642168%2C3268229089%2C3541565459&frm=20&eoidce=1&td=1&egid=16524&tan=6156e5d4-379d-4b6e-8367-3ad443808ca6%2C6156e5d4-379d-4b6e-8367-3ad443808ca7%2C6156e5d4-379d-4b6e-8367-3ad443808ca8%2C6156e5d4-379d-4b6e-8367-3ad443808ca9&tdf=2' \
  -H 'sec-ch-ua-platform: "Windows"' \
  -H 'Referer: https://www.irctc.co.in/' \
  -H 'User-Agent: Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/135.0.0.0 Safari/537.36' \
  -H 'Accept: */*' \
  -H 'sec-ch-ua: "Google Chrome";v="135", "Not-A.Brand";v="8", "Chromium";v="135"' \
  -H 'sec-ch-ua-mobile: ?0' ;




curl 'data:image/jpg;base64,iVBORw0KGgoAAAANSUhEUgAAAMsAAAAyCAYAAADyZi/iAAAGRElEQVR42u1db2RcWRSPURGVL7Eiao0SFRGjSq2KiigVMSqqVD9URZTYD2s/7dcVVUusqFhVVlWtilAVERFL1YiKClWxVsVQtVZElDFGxBiPt/funlk3x3nv3XvnzsydN+fHkWTmnvvv3d+955x770tPD4PBYDAYDAaDwWAwGAwGg8FgMBiMTkEYhqNCHgp5LaQipCakCr+/FfKbkFkh2Q5oy2Uhy0J2hBxDW06EFKEdU/zE0zNwT6HJZX0tZD00gG69XUKzLUNCNjWz3BOS49HGZNEtZ0pI2dXAbSdZRJIxIUeG2cpVc4JHHJMlqYzrYJ6okGbLPbnaKOkGhdwW8kpI4CNZoI4HSGUfzMazkOYstK2I0pWEDPOoY7JE5Z+FQVKHJM19Db3zQlab3PYfCa48S9B5QZC+PyJtP/hgKgo86pgsUflvoSLuedLuKYIo74X0xehcQOmlQ38uoZxzkE7FJI88JgvOewJlv+ZJm+Vq94UwkbIJegtIZ1mzvGWkt9ENAysvTQMhh0qIcA/CoF/F6N0g9P4Q8nPSzITymRSyIuRvJdx6AHnnPSQLXlVyHjzDXlhBMK5r6OLo17TBuFER1P2b1M204NS9SfALv+DlFcKLOwl6paRYPJS/peGbFmSZJiRoFlnk5FF30gEfPHm+T4l+W9DUrSC9Pk29PqLMmdSRRWBAyJ8G4cERxVY90NQ7iZp1gShFg2DOJxio7SbLHZT1ogfPdo7orw0D/ZptXxHlLqaRLC/hp4yrf1c3m2A5nwXTCs/uGTmTwt+HmnrvIupTIJbwRYj1Z0ByYNLVZ/I1D8jyK8r6Jnwu6zsvBylMLgFMFp/AxMw36blegnLwxDLQJrK8SiNZ6nH0wYj0I+A7nOoIS72rKM08EX0Zj6n7OBF5aRdZsH2fg/p91lgdPwq54rAu0jr4i1jNLxrm49IM+5BGssiZbyxB53GE3miC3hOks4S+xwNLZ39i3hOyYBN0ipgckkzTaUd1ofy9uxb5vHHk4EuU00iWVQ2dG4TeioXeFop8qSgatGHfA7KcEIGMpB3v/SgfsIF6UBuPjy3zemQZOn5E1KGaRrLc0lzmXeiVle+W0HcPDNqw4AFZ4iJ2cTve2652vCM2HneFnLHM7wpB5qEEnSHCfPv3JEMayTKkoZNxpFeNsfnzBm3Ie0qWY8vB9Y1F+dTG45HOc0nIF5N525D86SVLi/UC5XP8oE2iNgMekIXyT2zNliXDsqM2Hq85aNcoYWLugxnZH2NWlrBPxmRxpIcHm2EbMh6QhTqOb+sQFwzLpjYef3DYthniFHUc5LOcxqsck8UdWWqNDGIPyLJLDJpey1BrxaDcuVbsaYD/8lFzk3gcVqR0nQ/jlcVZP641krdN5Ag2HrH5V4zyKRyuMitAipri+G9AGP8MpLuJ6vWUyeKOLKUO91l+aiVZIjYejxsNPTexP+4wWdyRpdOjYTOESWK7413R0KE2Hm97NK7eow3rASaLO7J0+j5LL+EE2zr4v5u2Vzfy1qIxNYbqttmTBnhElmsN7OAX200WyHvd0WWpBzFppwmibHs2pl66DmEzWZAecTbsW4387vtwNgzynrS8hos3JUci0mYJ3+6w0Y1Hx31wF9XvdU9a4BlZqFPHEzF5TRAbZm0jC+RfaPAFD6sxZt4ecXh1vEUrxXmNdHPoAlxZR4/JYqkXd59FSZODzwJ0RcAHslCzfxEOUvYrJJklzMeDmCsOz4g54fsWjpEA+vmWupKF/71IULblHT7eEqbt7ZQekmWQOkUcg8/ETclAt/wmvWvrasRhwjgcxd3ZD5sMk2emgXKYxte4+kYWhTAbmnfwB4l8T9pJFihnRLk9moRNjQOXnUKW9VSZXr6TBTnMK7D5FoDIN72sqmFZOMh3yultN1mU8uTbKZ/DUZGqctFrF6Jgl236rcVkGQZ/5AX4YBXlecjf5QvPHyZdGmT4QXh8qWyNe4XBoMmCrysvcK8wGLRvgHfOL3HPMLqFANJJHNZId4E4TLjDPcjoJrL8fwcCXl4nHcwMfNcHZ6l+IY6n10L+JzqMLiWLCQKfTt0yGL6SZc/mJQ8MRhrIkoUjFM/h3kYJ9iaqIGV4AdxyyP+KjcFgMBgMBoPBYDAYDAaj+/APBn+RUcehWEYAAAAASUVORK5CYII=' \
  -H 'User-Agent: Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/135.0.0.0 Safari/537.36' \
  -H 'Referer;' ;




curl 'https://securepubads.g.doubleclick.net/gampad/ads?pvsid=632509865837418&correlator=3138997595635122&eid=95353385%2C31091816%2C95355263%2C83321073%2C31086809%2C31061691%2C31061692&output=ldjh&gdfp_req=1&vrg=202504160101&ptt=17&impl=fifs&iu_parts=37179215%2CGPT_IRCTC_PASSENGER_DETAIL_CAPTCHA_300X250%2CGPT_NWEB_REVIEW_BOOKING_TOP%2CGPT_NWEB_REVIEW_BOOKING_BOTTOM%2CGPT_NWEB_REVIEW_BOOKING_RIGHT&enc_prev_ius=%2F0%2F1%2C%2F0%2F2%2C%2F0%2F3%2C%2F0%2F4&prev_iu_szs=300x250%2C970x90%2C728x90%2C300x600%7C300x250%7C160x600%7C120x600&ifi=23&didk=3351422080~3952156613~3952155596~3952178929&dids=div-gpt-ad-1658133440721-0~div-gpt-ad-509520-0~div-gpt-ad-509521-0~div-gpt-ad-509522-0&adfs=2094388751~1281992877~1317729197~1075613749&sfv=1-0-41&sc=1&cookie_enabled=1&abxe=1&dt=1745041687257&lmt=1744719295&adxs=-12245933%2C-12245933%2C-12245933%2C-12245933&adys=-12245933%2C-12245933%2C-12245933%2C-12245933&biw=1203&bih=912&scr_x=0&scr_y=577&btvi=-1%7C-1%7C-1%7C-1&ucis=n%7Co%7Cp%7Cq&oid=2&u_his=40&u_h=864&u_w=1536&u_ah=816&u_aw=1536&u_cd=24&u_sd=1&u_tz=330&dmc=8&bc=31&nvt=1&uach=WyJXaW5kb3dzIiwiMTkuMC4wIiwieDg2IiwiIiwiMTM1LjAuNzA0OS45NiIsbnVsbCwwLG51bGwsIjY0IixbWyJHb29nbGUgQ2hyb21lIiwiMTM1LjAuNzA0OS45NiJdLFsiTm90LUEuQnJhbmQiLCI4LjAuMC4wIl0sWyJDaHJvbWl1bSIsIjEzNS4wLjcwNDkuOTYiXV0sMF0.&uas=3&url=https%3A%2F%2Fwww.irctc.co.in%2Fnget%2Fbooking%2FreviewBooking&ref=https%3A%2F%2Fwww.irctc.co.in%2Fnget%2Ferror&rumc=632509865837418&rume=1&vis=1&psz=300x92%7C1203x90%7C872x35%7C300x196&msz=0x0%7C0x0%7C0x0%7C0x0&fws=128%2C128%2C128%2C128&ohw=0%2C0%2C0%2C0&topics=3&tps=3&htps=10&nt=1&psd=WzMxLFtdLG51bGwsM10.&dlt=1745041486247&idt=1661&prev_scp=%7CDestination%3DPNBE%26Quota%3DTQ%26Departure%3D20042025%26Meal%3D0%26Gender%3DM%26TrainType%3DO%26Arrival%3D21042025%26Age%3D66%26Source%3DKYN%26Classes%3D3E%7CDestination%3DPNBE%26Quota%3DTQ%26Departure%3D20042025%26Meal%3D0%26Gender%3DM%26TrainType%3DO%26Arrival%3D21042025%26Age%3D66%26Source%3DKYN%26Classes%3D3E%7CDestination%3DPNBE%26Quota%3DTQ%26Departure%3D20042025%26Meal%3D0%26Gender%3DM%26TrainType%3DO%26Arrival%3D21042025%26Age%3D66%26Source%3DKYN%26Classes%3D3E&adks=607550432%2C2470642168%2C3268229089%2C3541565459&frm=20&eoidce=1&td=1&egid=16524&tan=6156e5d4-379d-4b6e-8367-3ad443808ca6%2C6156e5d4-379d-4b6e-8367-3ad443808ca7%2C6156e5d4-379d-4b6e-8367-3ad443808ca8%2C6156e5d4-379d-4b6e-8367-3ad443808ca9&tdf=2' \
  -H 'sec-ch-ua-platform: "Windows"' \
  -H 'Referer: https://www.irctc.co.in/' \
  -H 'User-Agent: Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/135.0.0.0 Safari/537.36' \
  -H 'sec-ch-ua: "Google Chrome";v="135", "Not-A.Brand";v="8", "Chromium";v="135"' \
  -H 'sec-ch-ua-mobile: ?0' ;




curl 'https://www.google-analytics.com/g/collect?v=2&tid=G-NFN218243Z&gtm=45je54g3v872522363za200zb9117897900&_p=1745041486402&gcd=13l3l3l3l1l1&npa=0&dma=0&tag_exp=102803279~102813109~102887800~102926062~103027016~103051953~103055465~103077950~103106314~103106316&cid=1504996631.1745039630&ul=en-us&sr=1536x864&uaa=x86&uab=64&uafvl=Google%2520Chrome%3B135.0.7049.96%7CNot-A.Brand%3B8.0.0.0%7CChromium%3B135.0.7049.96&uamb=0&uam=&uap=Windows&uapv=19.0.0&uaw=0&are=1&frm=0&pscdl=noapi&_eu=AEAAAAI&_s=7&dl=https%3A%2F%2Fwww.irctc.co.in%2Fnget%2Fbooking%2FreviewBooking&dr=https%3A%2F%2Fwww.irctc.co.in%2Fnget%2Fbooking%2Fpsgninput&sid=1745039630&sct=1&seg=1&dt=IRCTC%20Next%20Generation%20eTicketing%20System&en=page_view&_et=25056&tfd=207090' \
  -X 'POST' \
  -H 'accept: */*' \
  -H 'accept-language: en-US,en;q=0.9,de;q=0.8,zh-CN;q=0.7,zh;q=0.6' \
  -H 'cache-control: no-cache' \
  -H 'content-length: 0' \
  -b 'ar_debug=1' \
  -H 'origin: https://www.irctc.co.in' \
  -H 'pragma: no-cache' \
  -H 'priority: u=1, i' \
  -H 'referer: https://www.irctc.co.in/' \
  -H 'sec-ch-ua: "Google Chrome";v="135", "Not-A.Brand";v="8", "Chromium";v="135"' \
  -H 'sec-ch-ua-mobile: ?0' \
  -H 'sec-ch-ua-platform: "Windows"' \
  -H 'sec-fetch-dest: empty' \
  -H 'sec-fetch-mode: no-cors' \
  -H 'sec-fetch-site: cross-site' \
  -H 'sec-fetch-storage-access: active' \
  -H 'user-agent: Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/135.0.0.0 Safari/537.36' ;




curl 'https://www.google-analytics.com/g/collect?v=2&tid=G-NFN218243Z&gtm=45je54g3v872522363za200zb9117897900&_p=1745041486402&gcd=13l3l3l3l1l1&npa=0&dma=0&tag_exp=102803279~102813109~102887800~102926062~103027016~103051953~103055465~103077950~103106314~103106316&cid=1504996631.1745039630&ul=en-us&sr=1536x864&uaa=x86&uab=64&uafvl=Google%2520Chrome%3B135.0.7049.96%7CNot-A.Brand%3B8.0.0.0%7CChromium%3B135.0.7049.96&uamb=0&uam=&uap=Windows&uapv=19.0.0&uaw=0&are=1&frm=0&pscdl=noapi&_eu=AEAAAAI&_s=7&dl=https%3A%2F%2Fwww.irctc.co.in%2Fnget%2Fbooking%2FreviewBooking&dr=https%3A%2F%2Fwww.irctc.co.in%2Fnget%2Fbooking%2Fpsgninput&sid=1745039630&sct=1&seg=1&dt=IRCTC%20Next%20Generation%20eTicketing%20System&en=page_view&_et=25056&tfd=207090' \
  -X 'POST' \
  -H 'sec-ch-ua-platform: "Windows"' \
  -H 'Referer: https://www.irctc.co.in/' \
  -H 'User-Agent: Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/135.0.0.0 Safari/537.36' \
  -H 'sec-ch-ua: "Google Chrome";v="135", "Not-A.Brand";v="8", "Chromium";v="135"' \
  -H 'sec-ch-ua-mobile: ?0' ;




curl 'https://www.google-analytics.com/g/collect?v=2&tid=G-7K0RMWL72E&gtm=45je54g3v9116751228za200&_p=1745041486402&gcd=13l3l3l3l1l1&npa=0&dma=0&tag_exp=102803279~102813109~102887800~102926062~103027016~103051953~103055465~103077950~103106314~103106316&cid=1504996631.1745039630&ul=en-us&sr=1536x864&uaa=x86&uab=64&uafvl=Google%2520Chrome%3B135.0.7049.96%7CNot-A.Brand%3B8.0.0.0%7CChromium%3B135.0.7049.96&uamb=0&uam=&uap=Windows&uapv=19.0.0&uaw=0&are=1&frm=0&pscdl=noapi&_eu=AEAIAAI&_s=8&dl=https%3A%2F%2Fwww.irctc.co.in%2Fnget%2Fbooking%2FreviewBooking&dr=https%3A%2F%2Fwww.irctc.co.in%2Fnget%2Fbooking%2Fpsgninput&sid=1745041477&sct=1&seg=1&dt=IRCTC%20Next%20Generation%20eTicketing%20System&en=page_view&_et=25048&tfd=207108' \
  -X 'POST' \
  -H 'sec-ch-ua-platform: "Windows"' \
  -H 'Referer: https://www.irctc.co.in/' \
  -H 'User-Agent: Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/135.0.0.0 Safari/537.36' \
  -H 'sec-ch-ua: "Google Chrome";v="135", "Not-A.Brand";v="8", "Chromium";v="135"' \
  -H 'sec-ch-ua-mobile: ?0' ;




curl 'https://www.google-analytics.com/g/collect?v=2&tid=G-7K0RMWL72E&gtm=45je54g3v9116751228za200&_p=1745041486402&gcd=13l3l3l3l1l1&npa=0&dma=0&tag_exp=102803279~102813109~102887800~102926062~103027016~103051953~103055465~103077950~103106314~103106316&cid=1504996631.1745039630&ul=en-us&sr=1536x864&uaa=x86&uab=64&uafvl=Google%2520Chrome%3B135.0.7049.96%7CNot-A.Brand%3B8.0.0.0%7CChromium%3B135.0.7049.96&uamb=0&uam=&uap=Windows&uapv=19.0.0&uaw=0&are=1&frm=0&pscdl=noapi&_eu=AEAIAAI&_s=8&dl=https%3A%2F%2Fwww.irctc.co.in%2Fnget%2Fbooking%2FreviewBooking&dr=https%3A%2F%2Fwww.irctc.co.in%2Fnget%2Fbooking%2Fpsgninput&sid=1745041477&sct=1&seg=1&dt=IRCTC%20Next%20Generation%20eTicketing%20System&en=page_view&_et=25048&tfd=207108' \
  -X 'POST' \
  -H 'accept: */*' \
  -H 'accept-language: en-US,en;q=0.9,de;q=0.8,zh-CN;q=0.7,zh;q=0.6' \
  -H 'cache-control: no-cache' \
  -H 'content-length: 0' \
  -b 'ar_debug=1' \
  -H 'origin: https://www.irctc.co.in' \
  -H 'pragma: no-cache' \
  -H 'priority: u=1, i' \
  -H 'referer: https://www.irctc.co.in/' \
  -H 'sec-ch-ua: "Google Chrome";v="135", "Not-A.Brand";v="8", "Chromium";v="135"' \
  -H 'sec-ch-ua-mobile: ?0' \
  -H 'sec-ch-ua-platform: "Windows"' \
  -H 'sec-fetch-dest: empty' \
  -H 'sec-fetch-mode: no-cors' \
  -H 'sec-fetch-site: cross-site' \
  -H 'sec-fetch-storage-access: active' \
  -H 'user-agent: Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/135.0.0.0 Safari/537.36' ;




curl 'https://www.irctc.co.in/eticketing/protected/mapps1/captchaverify/m9nsqq1e/BOOKINGWS/mgL6z9' \
  -H 'accept: application/json, text/plain, */*' \
  -H 'accept-language: en-US,en;q=0.7' \
  -H 'authorization: Bearer 28ba394c-45f4-4707-a75f-a28c8c2d1692' \
  -H 'bmirak: webbm' \
  -H 'bmiyek: BC2382828765A1F05358C89A6038C0FF' \
  -H 'cache-control: no-cache' \
  -H 'content-language: en' \
  -H 'content-type: application/x-www-form-urlencoded' \
  -b $'bm_ss=ab8e18ef4e; _gid=GA1.3.848614353.1745039630; _gcl_au=1.1.62160036.1745041395; _ga_R24JMMNBXX=GS1.1.1745041395.1.0.1745041395.60.0.0; bm_so=BAD45DE45A27169F689873389A1A82BB7952586A65292A3EAE54527244F77F26~YAAQNUYDF1s0uCKWAQAAZ9CTTAOZm709KRc4fkcke198+g+g1PSx8UnGUu+G9fHsf16sbKdiOS7O9kD9krxPsK8I85A9um9Tr+9THtXVK7fRKM/Wa46Ysen1OWZBmKKlF96CGhTHQ+Pjm8Xe6uhuoWmJ2WX4plWQ+utE/kBvrJ5TdnKUO4UNgHCB2jY/k4vWM1eNSEQLEZnb7ba/dr70JC5z5BhpRp4NOvsdPu4VKC1WK2MVpGd2jFYNUKDDYY/uNtjQZzdd0KiMTPw+DXVb2B8QY1nYGtzOOZ5ljLJxvcWftY3WdS8v9/Sx9dHM79GNpGTrYBDw9SvG6Me/6vNSqZKcHuF5EtvYW75ac3XnEN4v6pMkrj61uyu0qRDq3gjivfhLK9D2a9xulsvs3eu/aIuDwWWkh78i4oMKYyq2UBh29kl5sc34qOUQhOHwroAc2/e3hLpgghlCdmsLYl7O6KSSSg==; _ga=GA1.1.1504996631.1745039630; _ga_JSTMKS9Y3J=GS1.1.1745039631.1.1.1745041488.0.0.0; bm_lso=BAD45DE45A27169F689873389A1A82BB7952586A65292A3EAE54527244F77F26~YAAQNUYDF1s0uCKWAQAAZ9CTTAOZm709KRc4fkcke198+g+g1PSx8UnGUu+G9fHsf16sbKdiOS7O9kD9krxPsK8I85A9um9Tr+9THtXVK7fRKM/Wa46Ysen1OWZBmKKlF96CGhTHQ+Pjm8Xe6uhuoWmJ2WX4plWQ+utE/kBvrJ5TdnKUO4UNgHCB2jY/k4vWM1eNSEQLEZnb7ba/dr70JC5z5BhpRp4NOvsdPu4VKC1WK2MVpGd2jFYNUKDDYY/uNtjQZzdd0KiMTPw+DXVb2B8QY1nYGtzOOZ5ljLJxvcWftY3WdS8v9/Sx9dHM79GNpGTrYBDw9SvG6Me/6vNSqZKcHuF5EtvYW75ac3XnEN4v6pMkrj61uyu0qRDq3gjivfhLK9D2a9xulsvs3eu/aIuDwWWkh78i4oMKYyq2UBh29kl5sc34qOUQhOHwroAc2/e3hLpgghlCdmsLYl7O6KSSSg==^1745041489247; ngetAppId=dZRMlECgRX6QjJnYek1SEhlD2VqSWrchYx670hbEHr_Zs5Ta_69w\u0021-735474581; et_appVIP1=1057115658.17439.0000; TS018d84e5=01d83d9ce78206a02c312d3e325088361666f560be2ac8f71d3d44dc3efb51c9726d32c3e5f6105be3e1cf7bf5d8a2154746d67548; _ga_SHTZYKNHG2=GS1.1.1745039630.1.1.1745041565.0.0.0; bm_s=YAAQN0YDF8upOkeWAQAA5RmVTAPXpsYUmwNnR8QQ+/sonrlAPsrIG6zABEy8N9AuBf8m0RRBzl1Y1NNzCyWFplAwXi3K4B3ap0T6Vsz8EP8b6nt6QeXo4i9q/J9+GL6EgAbLloXlJOOVtVbbQwqZA1dvCdyY+bmMIxqIDvAgCJDHU8+E76BH20oClrACwf9pqH+jF3veP2Fplz/M4DJkb47mJJP5cWyYJKf9hPMnELssWCuueazXn0YSItxCaKkG+aHX2RJ0zUulgLeF9AQLLCUDpSoQpEn6EaYEcOS6U0fVZ1wVVcCQvXVb4k0o6q5ew1n7rT7eVbtvQlL0DDBOmaPv1d/nH2Zhpsh/mB1Zl9Vhfv+QsI0ozE+cnHOpuTgHwBtT1RtMyE9SX3aGLklUhZGZCiYQpsziK06me0UcbGA/3ZTx7xUDd7DHwxVWVY17Ir5vTrnPz+vvFWzLluL31g==; RT="z=1&dm=www.irctc.co.in&si=ea039a6d-d875-467f-addb-848d12641828&ss=m9nrjeng&sl=5&tt=1lay&bcn=%2F%2F684d0d49.akstat.io%2F&ld=13vjz&nu=9y8m6cy&cl=17qzq"; _abck=D8B6F63CDAF4608955AFCC122AF2B6F6~0~YAAQFkYDFyPJb0qWAQAAR+GWTA2YoS4R1xWT4hyD9Yunw5NqQ2TYrDktxlDEIhKM48V+wICeJN6BH3XKKU7rpRAjWNkrpr5XT+SVroOB2VTWNA30wUvX7P+3aTVinQDUHME9PXRSdV6PiPzvjlC21ZuFSSOIKhKt9J+S4TJ9viywzoSHbRGS8JqOLpnY8wCCollwS3KuhiYsM+30IvHAOtIWt1ogBZbIax/Wem+DT5iuSkGzWAWM55bye85YUFZ0LvRhkmt/cZCXuuAv8hPeO0Fd6w8dDZAU+MkKxAyfiEsfM87AWJxZMAOpjbLf/cC0vDyz2aQfRrNpYD6ISNm+iuP61J87fqhnVA0mYSfmdhmTPRExbBMNR7czwTR6fsyiMzXWMfadE/qe6VJM88z8hQ5hJEMRauAzlxg9360rNMCcBRxgv4hDIdaU3d1D5gX/uc0PZbNFX10pn+tTEzon4eoSd8ynyYmf8CbsAvPLQjKxfFs51hGwzlpu1jNZ4M4GDDgggg/J63t2crAnDgslK0TfHVj3O1ldHVXR5yG0Q51++vG2y8rg50qwjvtH4sBAogcdf+b9N3xOG9DxXBJosWHjyO8LbWf3GYYmmgbX8bgTadfv8dx6Asx5vDRECVbyntpkX9JP16typV6W2m/FLrnwYJI9aLDHJ4AfqHlFjqxQcuHQxvNVa1Y3hd99BlfLE6yeFJUzm2YFas9oseD4WXwqMhVVg4Ub/EysZH1IcHr/e3VKiF1wIaGinJ+C7BIBNZoImLd+koCKvQsAfh9wWeVy5qawreJbRIp0HT7yP7fBTf42LxVzKPjmrkIVdFwJq6+PRzlUN/Bcfi4Nkk3pu8ScR6knrNrLDi44RqN37Cnwf2Pu9I2s3C9RR9M+tzy9/IU=~-1~-1~1745043221; bm_sz=1C014777F8FA015BACD38209C2F65F4C~YAAQFkYDFyTJb0qWAQAAR+GWTBtXbW4Mii6OXAx31IDtlfAb6APPMEu07oSosJyFRpiQk113DUMPmTZjEuwcqFKCxhykjrhIHFLPzYLMXFawJXngQ6s59yEBZut7/rm/w4p2h/yeq50I6efhW9gw+4nATk2T1eyfr+X5FYba4CPS8n11vCIMzONPqyz4TaKIDWk5l1dvdsZpaPueqI1d7DXkn07IlpoNzs+GGTUs42BEc24M+8svtx9+5HB8Fvrxp3HskUhzgnRCq8fpZo6dHKhaOSJEVHnXvORE6uP7AltPzaCJzqPVyWEvvJmU2wHbmZAoPSwTeA21hEYAgbGVggujbwVac4/L+FbSuizJYjr1b1nyVJQXtWt+kRTmhtI1D7hafDl+NsZlScClqRDNaCf1DwYpV8VCpFN4sUIz2LYHVfQrB6c3fu4YzuDH+xY2+TpQ6X+ouDQFQUWrJBiFdGKNyWlCbbEIHbAiW5k=~4340038~4277825; _ga_NFN218243Z=GS1.1.1745039630.1.1.1745041688.0.0.0; _ga_7K0RMWL72E=GS1.1.1745041477.1.1.1745041688.0.0.0' \
  -H 'greq: GQ:9a2f301b-0467-4bf3-91b9-b0230d6f4179' \
  -H 'pragma: no-cache' \
  -H 'priority: u=1, i' \
  -H 'referer: https://www.irctc.co.in/nget/booking/reviewBooking' \
  -H 'sec-ch-ua: "Google Chrome";v="135", "Not-A.Brand";v="8", "Chromium";v="135"' \
  -H 'sec-ch-ua-mobile: ?0' \
  -H 'sec-ch-ua-platform: "Windows"' \
  -H 'sec-fetch-dest: empty' \
  -H 'sec-fetch-mode: cors' \
  -H 'sec-fetch-site: same-origin' \
  -H 'spa-csrf-token: 1745041678486-1534027541' \
  -H 'user-agent: Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/135.0.0.0 Safari/537.36' ;




curl 'https://www.irctc.co.in/eticketing/protected/mapps1/captchaverify/m9nsqq1e/BOOKINGWS/mgL6z9' \
  -H 'greq: GQ:9a2f301b-0467-4bf3-91b9-b0230d6f4179' \
  -H 'sec-ch-ua-platform: "Windows"' \
  -H 'Authorization: Bearer 28ba394c-45f4-4707-a75f-a28c8c2d1692' \
  -H 'bmirak: webbm' \
  -H 'Referer: https://www.irctc.co.in/nget/booking/reviewBooking' \
  -H 'spa-csrf-token: 1745041678486-1534027541' \
  -H 'Accept-Language: en-US,en;q=0.7' \
  -H 'sec-ch-ua: "Google Chrome";v="135", "Not-A.Brand";v="8", "Chromium";v="135"' \
  -H 'bmiyek: BC2382828765A1F05358C89A6038C0FF' \
  -H 'sec-ch-ua-mobile: ?0' \
  -H 'User-Agent: Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/135.0.0.0 Safari/537.36' \
  -H 'Accept: application/json, text/plain, */*' \
  -H 'Content-Type: application/x-www-form-urlencoded' \
  -H 'Content-Language: en' ;




curl 'data:image/jpg;base64,iVBORw0KGgoAAAANSUhEUgAAAMsAAAAyCAYAAADyZi/iAAAGwklEQVR42u1db2RcWRSPETFihFFj1IolKlbECrFWRFSoioiKUFVVVaX2Q+2H2i8VNaqWWlWjqqxaFRWhoiqiXyoiIqqMqqoVw4qoiCoREWOM4e2968zu3dPz7rv3vTd/3nvnx5GYd8697937fu+ee855M11dDAaDwWAwGAwGg8FgMBgMBoPBYIQDx3FyQmaF3BayJGRDyIGQqpAa/N0TsizkppCTAfsbFVIUsiXkGPqoCCkLWRBylmeF0alksUVdyAMhact+8kJWDft4L2TY7zWENRYBx8kYfBfGlywNlIScMOxjSMhny/aPhEwwWRidSJZ9Ib8LmRPSLyQFx3uETAtZJOb5taGbt4fstoVcEdILOr1CLoMrpkK6gwNMFkankEXuUWYa5PDQPUfM9bSHzTOkL/cqGRfdjJBNpL/eCWQJaaxvE+P3B9+F8SXXfTTZSxrdU0j32CtAII+DnorTUSeLDFy4uLJpvqviS5ZhNOGHGt0C0i0a9lFEditRJgu4tV8IF7Of76h4kyWFJr2m0cXRrynDPqaJCFxvFMkCe74SsaqcCaHtaQj37ysheBlJvKsLvoDbje0+CPnNJjUgV3zYy35CaYYlL/c8qRG0ikbvCOmmDdtPEzfXuYiS5QlxLYUg5wRBkzWPuMEX7L5C+H7Lw+7AK9cF/b8yiF2syz5bsR/sVKLgfchbjW7N7wARA38vamQRTVwlrmMl4DhkhXy0CL8PKnvBPUO7ilueC4hStgj2/SVXuaSS5Q667vkWkWU5SmQR5iNw0+EbJxtwHJ7DX5m3utFwm8DduwKuFX66S9f5nZIiMLF743I+64SLfA9yaSmQYXDp6qDzInFkkUlC8EsbkL5qX4vcsHdRIQs8/XeJp/X3Qc9JyVPlXPQH0Rw5UKrkx24c6VwnoptjmnMfIyKb8SULPHkmhTxWnhQNn3jUw3YtpA2+V9St08hC+fOXwjgnmIMhD5tHLnbfedg9Rjb30fEddPyawflfjy1ZDP3QZZOwJ9SQ+QkdPyD6rEaBLC6Jx0chzseSgc0MYbfow+4VinypKFtcw3YSyVKFPUvesK0fiQ1n3sMmT7hvXiHqjiCLS+LxrZDuEOdjztANDMPuUDmGk9F3LK6hkOSVpQ5L9gmD9jaQ7YZHucuGS58dTRaXxONn0weLxXzkDWxSIdlVlWOrNmVOXm51nPcscqM2T4Qed7zcMeknE1GhbSiczIBOo5ByG8X7TfM5bSWLJvE4GfbDq8V2deVz/CDIWrSZTWI0LKNEVhr46OVmQAFmzSI2L929KfyU7mCyUInHX5qx0rfLDkfKLK8hldhKayVm38ANw/3Ln4ZJrDFYkYySee0ki0vicblZbnEbyVILuJ9LLFlwqf6ape0ikKKmbPxXIMzYDXqzqI8nmjbrIUSxjGveFJsRIjdRdtuT8cqSTLL0mO4nAvTxK+rjgkYXJ74yPvrL4ISbgR++SyTpBpsZcGkjWQ54zxLOJNaa0H4JRd+yGt036HzO+ugP75FKHvpU4vF8s6OTbSQLR8N8TmAfzp+E3P4Qan/VQ38h6OYavrlGxYJGt0AQpdiCh1I7ycJ5Fp8TeNn2XXzL9p/bhGCli2ZaCW24kklcNFyB/skdtWgFbydZJgNk8MtJrTpOE1GtmyG2f8nHl2J0Ez71nEWfs8Q7HT2EXj/Rz37QxGMUyALHcG3YTwbtXYtFbRj43aMW+nmiOPJAV3msrBTfGoZh1cjWoYkd2N4izmvcwG6cIMAtl6DGe6KSYayFe8N2k4WqOp7QtDVBJKQjS5YGPkDN1wwQIqXo5ODzhy7l1jOG/dQhoTmnPonF/9/A+xR4k16z2ahDeHKTOL8FOP8+RbcXPntK6G9S33Qjv4WF0P25xYEUp912uvdZFJ1h+KyOXhGIBVn8oKIL5wbs59BnRCvrQhhTbLpF3ZwmI0JkyVFVxBrsEG9K1pNCljp8IcFAk/p5aep6aVaYeZfKZd3rtwVH891pTJavCLNi+A5+jmi3EkWy5MEtugsE2IKnek2p0TqGSNEi+KwnffQzAPuRZ9DHEZCuDv+/hnMYCvHa5B7jIpx3Ca6j0WcFSnYWQSfd5FU4VmRRdE/DGO4qY/sJ7qUp5Pb+LyjSxWAwSFLhl8pe8KgwGDRZ8OvKBR4VBuNrogwSr2eM8MgwkkKAl47ZrxucIopNt3gEGUkiy7/vGEGp0YDz30+UpKFw8iHx+kLNsfiRKgYjTmSxTTmc59FjMFn0kGVCP/DIMZJIln4oUXoK9YUHkLuqghxCDWHRMfypQwaDwWAwGAwGg8FgMBgMK/wNedNMweJDFZ8AAAAASUVORK5CYII=' \
  -H 'User-Agent: Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/135.0.0.0 Safari/537.36' \
  -H 'Referer;' ;




curl 'https://www.irctc.co.in/eticketing/protected/mapps1/captchaverify/m9nsqq1e/BOOKINGWS/39UZmg' \
  -H 'accept: application/json, text/plain, */*' \
  -H 'accept-language: en-US,en;q=0.7' \
  -H 'authorization: Bearer 28ba394c-45f4-4707-a75f-a28c8c2d1692' \
  -H 'bmirak: webbm' \
  -H 'bmiyek: BC2382828765A1F05358C89A6038C0FF' \
  -H 'cache-control: no-cache' \
  -H 'content-language: en' \
  -H 'content-type: application/x-www-form-urlencoded' \
  -b $'bm_ss=ab8e18ef4e; _gid=GA1.3.848614353.1745039630; _gcl_au=1.1.62160036.1745041395; _ga_R24JMMNBXX=GS1.1.1745041395.1.0.1745041395.60.0.0; bm_so=BAD45DE45A27169F689873389A1A82BB7952586A65292A3EAE54527244F77F26~YAAQNUYDF1s0uCKWAQAAZ9CTTAOZm709KRc4fkcke198+g+g1PSx8UnGUu+G9fHsf16sbKdiOS7O9kD9krxPsK8I85A9um9Tr+9THtXVK7fRKM/Wa46Ysen1OWZBmKKlF96CGhTHQ+Pjm8Xe6uhuoWmJ2WX4plWQ+utE/kBvrJ5TdnKUO4UNgHCB2jY/k4vWM1eNSEQLEZnb7ba/dr70JC5z5BhpRp4NOvsdPu4VKC1WK2MVpGd2jFYNUKDDYY/uNtjQZzdd0KiMTPw+DXVb2B8QY1nYGtzOOZ5ljLJxvcWftY3WdS8v9/Sx9dHM79GNpGTrYBDw9SvG6Me/6vNSqZKcHuF5EtvYW75ac3XnEN4v6pMkrj61uyu0qRDq3gjivfhLK9D2a9xulsvs3eu/aIuDwWWkh78i4oMKYyq2UBh29kl5sc34qOUQhOHwroAc2/e3hLpgghlCdmsLYl7O6KSSSg==; _ga=GA1.1.1504996631.1745039630; _ga_JSTMKS9Y3J=GS1.1.1745039631.1.1.1745041488.0.0.0; bm_lso=BAD45DE45A27169F689873389A1A82BB7952586A65292A3EAE54527244F77F26~YAAQNUYDF1s0uCKWAQAAZ9CTTAOZm709KRc4fkcke198+g+g1PSx8UnGUu+G9fHsf16sbKdiOS7O9kD9krxPsK8I85A9um9Tr+9THtXVK7fRKM/Wa46Ysen1OWZBmKKlF96CGhTHQ+Pjm8Xe6uhuoWmJ2WX4plWQ+utE/kBvrJ5TdnKUO4UNgHCB2jY/k4vWM1eNSEQLEZnb7ba/dr70JC5z5BhpRp4NOvsdPu4VKC1WK2MVpGd2jFYNUKDDYY/uNtjQZzdd0KiMTPw+DXVb2B8QY1nYGtzOOZ5ljLJxvcWftY3WdS8v9/Sx9dHM79GNpGTrYBDw9SvG6Me/6vNSqZKcHuF5EtvYW75ac3XnEN4v6pMkrj61uyu0qRDq3gjivfhLK9D2a9xulsvs3eu/aIuDwWWkh78i4oMKYyq2UBh29kl5sc34qOUQhOHwroAc2/e3hLpgghlCdmsLYl7O6KSSSg==^1745041489247; ngetAppId=dZRMlECgRX6QjJnYek1SEhlD2VqSWrchYx670hbEHr_Zs5Ta_69w\u0021-735474581; et_appVIP1=1057115658.17439.0000; TS018d84e5=01d83d9ce78206a02c312d3e325088361666f560be2ac8f71d3d44dc3efb51c9726d32c3e5f6105be3e1cf7bf5d8a2154746d67548; _ga_SHTZYKNHG2=GS1.1.1745039630.1.1.1745041565.0.0.0; bm_s=YAAQN0YDF8upOkeWAQAA5RmVTAPXpsYUmwNnR8QQ+/sonrlAPsrIG6zABEy8N9AuBf8m0RRBzl1Y1NNzCyWFplAwXi3K4B3ap0T6Vsz8EP8b6nt6QeXo4i9q/J9+GL6EgAbLloXlJOOVtVbbQwqZA1dvCdyY+bmMIxqIDvAgCJDHU8+E76BH20oClrACwf9pqH+jF3veP2Fplz/M4DJkb47mJJP5cWyYJKf9hPMnELssWCuueazXn0YSItxCaKkG+aHX2RJ0zUulgLeF9AQLLCUDpSoQpEn6EaYEcOS6U0fVZ1wVVcCQvXVb4k0o6q5ew1n7rT7eVbtvQlL0DDBOmaPv1d/nH2Zhpsh/mB1Zl9Vhfv+QsI0ozE+cnHOpuTgHwBtT1RtMyE9SX3aGLklUhZGZCiYQpsziK06me0UcbGA/3ZTx7xUDd7DHwxVWVY17Ir5vTrnPz+vvFWzLluL31g==; RT="z=1&dm=www.irctc.co.in&si=ea039a6d-d875-467f-addb-848d12641828&ss=m9nrjeng&sl=5&tt=1lay&bcn=%2F%2F684d0d49.akstat.io%2F&ld=13vjz&nu=9y8m6cy&cl=17qzq"; _abck=D8B6F63CDAF4608955AFCC122AF2B6F6~0~YAAQFkYDFyPJb0qWAQAAR+GWTA2YoS4R1xWT4hyD9Yunw5NqQ2TYrDktxlDEIhKM48V+wICeJN6BH3XKKU7rpRAjWNkrpr5XT+SVroOB2VTWNA30wUvX7P+3aTVinQDUHME9PXRSdV6PiPzvjlC21ZuFSSOIKhKt9J+S4TJ9viywzoSHbRGS8JqOLpnY8wCCollwS3KuhiYsM+30IvHAOtIWt1ogBZbIax/Wem+DT5iuSkGzWAWM55bye85YUFZ0LvRhkmt/cZCXuuAv8hPeO0Fd6w8dDZAU+MkKxAyfiEsfM87AWJxZMAOpjbLf/cC0vDyz2aQfRrNpYD6ISNm+iuP61J87fqhnVA0mYSfmdhmTPRExbBMNR7czwTR6fsyiMzXWMfadE/qe6VJM88z8hQ5hJEMRauAzlxg9360rNMCcBRxgv4hDIdaU3d1D5gX/uc0PZbNFX10pn+tTEzon4eoSd8ynyYmf8CbsAvPLQjKxfFs51hGwzlpu1jNZ4M4GDDgggg/J63t2crAnDgslK0TfHVj3O1ldHVXR5yG0Q51++vG2y8rg50qwjvtH4sBAogcdf+b9N3xOG9DxXBJosWHjyO8LbWf3GYYmmgbX8bgTadfv8dx6Asx5vDRECVbyntpkX9JP16typV6W2m/FLrnwYJI9aLDHJ4AfqHlFjqxQcuHQxvNVa1Y3hd99BlfLE6yeFJUzm2YFas9oseD4WXwqMhVVg4Ub/EysZH1IcHr/e3VKiF1wIaGinJ+C7BIBNZoImLd+koCKvQsAfh9wWeVy5qawreJbRIp0HT7yP7fBTf42LxVzKPjmrkIVdFwJq6+PRzlUN/Bcfi4Nkk3pu8ScR6knrNrLDi44RqN37Cnwf2Pu9I2s3C9RR9M+tzy9/IU=~-1~-1~1745043221; bm_sz=1C014777F8FA015BACD38209C2F65F4C~YAAQFkYDFyTJb0qWAQAAR+GWTBtXbW4Mii6OXAx31IDtlfAb6APPMEu07oSosJyFRpiQk113DUMPmTZjEuwcqFKCxhykjrhIHFLPzYLMXFawJXngQ6s59yEBZut7/rm/w4p2h/yeq50I6efhW9gw+4nATk2T1eyfr+X5FYba4CPS8n11vCIMzONPqyz4TaKIDWk5l1dvdsZpaPueqI1d7DXkn07IlpoNzs+GGTUs42BEc24M+8svtx9+5HB8Fvrxp3HskUhzgnRCq8fpZo6dHKhaOSJEVHnXvORE6uP7AltPzaCJzqPVyWEvvJmU2wHbmZAoPSwTeA21hEYAgbGVggujbwVac4/L+FbSuizJYjr1b1nyVJQXtWt+kRTmhtI1D7hafDl+NsZlScClqRDNaCf1DwYpV8VCpFN4sUIz2LYHVfQrB6c3fu4YzuDH+xY2+TpQ6X+ouDQFQUWrJBiFdGKNyWlCbbEIHbAiW5k=~4340038~4277825; _ga_NFN218243Z=GS1.1.1745039630.1.1.1745041688.0.0.0; _ga_7K0RMWL72E=GS1.1.1745041477.1.1.1745041688.0.0.0' \
  -H 'greq: GQ:9a2f301b-0467-4bf3-91b9-b0230d6f4179' \
  -H 'pragma: no-cache' \
  -H 'priority: u=1, i' \
  -H 'referer: https://www.irctc.co.in/nget/booking/reviewBooking' \
  -H 'sec-ch-ua: "Google Chrome";v="135", "Not-A.Brand";v="8", "Chromium";v="135"' \
  -H 'sec-ch-ua-mobile: ?0' \
  -H 'sec-ch-ua-platform: "Windows"' \
  -H 'sec-fetch-dest: empty' \
  -H 'sec-fetch-mode: cors' \
  -H 'sec-fetch-site: same-origin' \
  -H 'spa-csrf-token: 1745041788560-1066986132' \
  -H 'user-agent: Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/135.0.0.0 Safari/537.36' ;




curl 'https://www.irctc.co.in/eticketing/protected/mapps1/captchaverify/m9nsqq1e/BOOKINGWS/39UZmg' \
  -H 'greq: GQ:9a2f301b-0467-4bf3-91b9-b0230d6f4179' \
  -H 'sec-ch-ua-platform: "Windows"' \
  -H 'Authorization: Bearer 28ba394c-45f4-4707-a75f-a28c8c2d1692' \
  -H 'bmirak: webbm' \
  -H 'Referer: https://www.irctc.co.in/nget/booking/reviewBooking' \
  -H 'spa-csrf-token: 1745041788560-1066986132' \
  -H 'Accept-Language: en-US,en;q=0.7' \
  -H 'sec-ch-ua: "Google Chrome";v="135", "Not-A.Brand";v="8", "Chromium";v="135"' \
  -H 'bmiyek: BC2382828765A1F05358C89A6038C0FF' \
  -H 'sec-ch-ua-mobile: ?0' \
  -H 'User-Agent: Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/135.0.0.0 Safari/537.36' \
  -H 'Accept: application/json, text/plain, */*' \
  -H 'Content-Type: application/x-www-form-urlencoded' \
  -H 'Content-Language: en' ;




curl 'https://www.irctc.co.in/nget/11-es2015.634413646e7a9e5ef025.js' \
  -H 'accept: */*' \
  -H 'accept-language: en-US,en;q=0.9,de;q=0.8,zh-CN;q=0.7,zh;q=0.6' \
  -H 'cache-control: no-cache' \
  -b $'bm_ss=ab8e18ef4e; _gid=GA1.3.848614353.1745039630; _gcl_au=1.1.62160036.1745041395; _ga_R24JMMNBXX=GS1.1.1745041395.1.0.1745041395.60.0.0; bm_so=BAD45DE45A27169F689873389A1A82BB7952586A65292A3EAE54527244F77F26~YAAQNUYDF1s0uCKWAQAAZ9CTTAOZm709KRc4fkcke198+g+g1PSx8UnGUu+G9fHsf16sbKdiOS7O9kD9krxPsK8I85A9um9Tr+9THtXVK7fRKM/Wa46Ysen1OWZBmKKlF96CGhTHQ+Pjm8Xe6uhuoWmJ2WX4plWQ+utE/kBvrJ5TdnKUO4UNgHCB2jY/k4vWM1eNSEQLEZnb7ba/dr70JC5z5BhpRp4NOvsdPu4VKC1WK2MVpGd2jFYNUKDDYY/uNtjQZzdd0KiMTPw+DXVb2B8QY1nYGtzOOZ5ljLJxvcWftY3WdS8v9/Sx9dHM79GNpGTrYBDw9SvG6Me/6vNSqZKcHuF5EtvYW75ac3XnEN4v6pMkrj61uyu0qRDq3gjivfhLK9D2a9xulsvs3eu/aIuDwWWkh78i4oMKYyq2UBh29kl5sc34qOUQhOHwroAc2/e3hLpgghlCdmsLYl7O6KSSSg==; _ga=GA1.1.1504996631.1745039630; _ga_JSTMKS9Y3J=GS1.1.1745039631.1.1.1745041488.0.0.0; bm_lso=BAD45DE45A27169F689873389A1A82BB7952586A65292A3EAE54527244F77F26~YAAQNUYDF1s0uCKWAQAAZ9CTTAOZm709KRc4fkcke198+g+g1PSx8UnGUu+G9fHsf16sbKdiOS7O9kD9krxPsK8I85A9um9Tr+9THtXVK7fRKM/Wa46Ysen1OWZBmKKlF96CGhTHQ+Pjm8Xe6uhuoWmJ2WX4plWQ+utE/kBvrJ5TdnKUO4UNgHCB2jY/k4vWM1eNSEQLEZnb7ba/dr70JC5z5BhpRp4NOvsdPu4VKC1WK2MVpGd2jFYNUKDDYY/uNtjQZzdd0KiMTPw+DXVb2B8QY1nYGtzOOZ5ljLJxvcWftY3WdS8v9/Sx9dHM79GNpGTrYBDw9SvG6Me/6vNSqZKcHuF5EtvYW75ac3XnEN4v6pMkrj61uyu0qRDq3gjivfhLK9D2a9xulsvs3eu/aIuDwWWkh78i4oMKYyq2UBh29kl5sc34qOUQhOHwroAc2/e3hLpgghlCdmsLYl7O6KSSSg==^1745041489247; ngetAppId=dZRMlECgRX6QjJnYek1SEhlD2VqSWrchYx670hbEHr_Zs5Ta_69w\u0021-735474581; et_appVIP1=1057115658.17439.0000; TS018d84e5=01d83d9ce78206a02c312d3e325088361666f560be2ac8f71d3d44dc3efb51c9726d32c3e5f6105be3e1cf7bf5d8a2154746d67548; _ga_SHTZYKNHG2=GS1.1.1745039630.1.1.1745041565.0.0.0; bm_s=YAAQN0YDF8upOkeWAQAA5RmVTAPXpsYUmwNnR8QQ+/sonrlAPsrIG6zABEy8N9AuBf8m0RRBzl1Y1NNzCyWFplAwXi3K4B3ap0T6Vsz8EP8b6nt6QeXo4i9q/J9+GL6EgAbLloXlJOOVtVbbQwqZA1dvCdyY+bmMIxqIDvAgCJDHU8+E76BH20oClrACwf9pqH+jF3veP2Fplz/M4DJkb47mJJP5cWyYJKf9hPMnELssWCuueazXn0YSItxCaKkG+aHX2RJ0zUulgLeF9AQLLCUDpSoQpEn6EaYEcOS6U0fVZ1wVVcCQvXVb4k0o6q5ew1n7rT7eVbtvQlL0DDBOmaPv1d/nH2Zhpsh/mB1Zl9Vhfv+QsI0ozE+cnHOpuTgHwBtT1RtMyE9SX3aGLklUhZGZCiYQpsziK06me0UcbGA/3ZTx7xUDd7DHwxVWVY17Ir5vTrnPz+vvFWzLluL31g==; RT="z=1&dm=www.irctc.co.in&si=ea039a6d-d875-467f-addb-848d12641828&ss=m9nrjeng&sl=5&tt=1lay&bcn=%2F%2F684d0d49.akstat.io%2F&ld=13vjz&nu=9y8m6cy&cl=17qzq"; _abck=D8B6F63CDAF4608955AFCC122AF2B6F6~0~YAAQFkYDFyPJb0qWAQAAR+GWTA2YoS4R1xWT4hyD9Yunw5NqQ2TYrDktxlDEIhKM48V+wICeJN6BH3XKKU7rpRAjWNkrpr5XT+SVroOB2VTWNA30wUvX7P+3aTVinQDUHME9PXRSdV6PiPzvjlC21ZuFSSOIKhKt9J+S4TJ9viywzoSHbRGS8JqOLpnY8wCCollwS3KuhiYsM+30IvHAOtIWt1ogBZbIax/Wem+DT5iuSkGzWAWM55bye85YUFZ0LvRhkmt/cZCXuuAv8hPeO0Fd6w8dDZAU+MkKxAyfiEsfM87AWJxZMAOpjbLf/cC0vDyz2aQfRrNpYD6ISNm+iuP61J87fqhnVA0mYSfmdhmTPRExbBMNR7czwTR6fsyiMzXWMfadE/qe6VJM88z8hQ5hJEMRauAzlxg9360rNMCcBRxgv4hDIdaU3d1D5gX/uc0PZbNFX10pn+tTEzon4eoSd8ynyYmf8CbsAvPLQjKxfFs51hGwzlpu1jNZ4M4GDDgggg/J63t2crAnDgslK0TfHVj3O1ldHVXR5yG0Q51++vG2y8rg50qwjvtH4sBAogcdf+b9N3xOG9DxXBJosWHjyO8LbWf3GYYmmgbX8bgTadfv8dx6Asx5vDRECVbyntpkX9JP16typV6W2m/FLrnwYJI9aLDHJ4AfqHlFjqxQcuHQxvNVa1Y3hd99BlfLE6yeFJUzm2YFas9oseD4WXwqMhVVg4Ub/EysZH1IcHr/e3VKiF1wIaGinJ+C7BIBNZoImLd+koCKvQsAfh9wWeVy5qawreJbRIp0HT7yP7fBTf42LxVzKPjmrkIVdFwJq6+PRzlUN/Bcfi4Nkk3pu8ScR6knrNrLDi44RqN37Cnwf2Pu9I2s3C9RR9M+tzy9/IU=~-1~-1~1745043221; bm_sz=1C014777F8FA015BACD38209C2F65F4C~YAAQFkYDFyTJb0qWAQAAR+GWTBtXbW4Mii6OXAx31IDtlfAb6APPMEu07oSosJyFRpiQk113DUMPmTZjEuwcqFKCxhykjrhIHFLPzYLMXFawJXngQ6s59yEBZut7/rm/w4p2h/yeq50I6efhW9gw+4nATk2T1eyfr+X5FYba4CPS8n11vCIMzONPqyz4TaKIDWk5l1dvdsZpaPueqI1d7DXkn07IlpoNzs+GGTUs42BEc24M+8svtx9+5HB8Fvrxp3HskUhzgnRCq8fpZo6dHKhaOSJEVHnXvORE6uP7AltPzaCJzqPVyWEvvJmU2wHbmZAoPSwTeA21hEYAgbGVggujbwVac4/L+FbSuizJYjr1b1nyVJQXtWt+kRTmhtI1D7hafDl+NsZlScClqRDNaCf1DwYpV8VCpFN4sUIz2LYHVfQrB6c3fu4YzuDH+xY2+TpQ6X+ouDQFQUWrJBiFdGKNyWlCbbEIHbAiW5k=~4340038~4277825; _ga_NFN218243Z=GS1.1.1745039630.1.1.1745041688.0.0.0; _ga_7K0RMWL72E=GS1.1.1745041477.1.1.1745041688.0.0.0' \
  -H 'pragma: no-cache' \
  -H 'priority: i' \
  -H 'referer: https://www.irctc.co.in/nget/booking/reviewBooking' \
  -H 'sec-ch-ua: "Google Chrome";v="135", "Not-A.Brand";v="8", "Chromium";v="135"' \
  -H 'sec-ch-ua-mobile: ?0' \
  -H 'sec-ch-ua-platform: "Windows"' \
  -H 'sec-fetch-dest: empty' \
  -H 'sec-fetch-mode: no-cors' \
  -H 'sec-fetch-site: same-origin' \
  -H 'user-agent: Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/135.0.0.0 Safari/537.36' ;




curl 'https://www.irctc.co.in/nget/11-es2015.634413646e7a9e5ef025.js' \
  -H 'sec-ch-ua-platform: "Windows"' \
  -H 'Referer: https://www.irctc.co.in/nget/booking/reviewBooking' \
  -H 'User-Agent: Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/135.0.0.0 Safari/537.36' \
  -H 'sec-ch-ua: "Google Chrome";v="135", "Not-A.Brand";v="8", "Chromium";v="135"' \
  -H 'sec-ch-ua-mobile: ?0' ;




curl 'https://www.irctc.co.in/nget/assets/images/Irctc%20Wallet.PNG' \
  -H 'accept: image/avif,image/webp,image/apng,image/svg+xml,image/*,*/*;q=0.8' \
  -H 'accept-language: en-US,en;q=0.9,de;q=0.8,zh-CN;q=0.7,zh;q=0.6' \
  -H 'cache-control: no-cache' \
  -b $'bm_ss=ab8e18ef4e; _gid=GA1.3.848614353.1745039630; _gcl_au=1.1.62160036.1745041395; _ga_R24JMMNBXX=GS1.1.1745041395.1.0.1745041395.60.0.0; bm_so=BAD45DE45A27169F689873389A1A82BB7952586A65292A3EAE54527244F77F26~YAAQNUYDF1s0uCKWAQAAZ9CTTAOZm709KRc4fkcke198+g+g1PSx8UnGUu+G9fHsf16sbKdiOS7O9kD9krxPsK8I85A9um9Tr+9THtXVK7fRKM/Wa46Ysen1OWZBmKKlF96CGhTHQ+Pjm8Xe6uhuoWmJ2WX4plWQ+utE/kBvrJ5TdnKUO4UNgHCB2jY/k4vWM1eNSEQLEZnb7ba/dr70JC5z5BhpRp4NOvsdPu4VKC1WK2MVpGd2jFYNUKDDYY/uNtjQZzdd0KiMTPw+DXVb2B8QY1nYGtzOOZ5ljLJxvcWftY3WdS8v9/Sx9dHM79GNpGTrYBDw9SvG6Me/6vNSqZKcHuF5EtvYW75ac3XnEN4v6pMkrj61uyu0qRDq3gjivfhLK9D2a9xulsvs3eu/aIuDwWWkh78i4oMKYyq2UBh29kl5sc34qOUQhOHwroAc2/e3hLpgghlCdmsLYl7O6KSSSg==; _ga=GA1.1.1504996631.1745039630; _ga_JSTMKS9Y3J=GS1.1.1745039631.1.1.1745041488.0.0.0; bm_lso=BAD45DE45A27169F689873389A1A82BB7952586A65292A3EAE54527244F77F26~YAAQNUYDF1s0uCKWAQAAZ9CTTAOZm709KRc4fkcke198+g+g1PSx8UnGUu+G9fHsf16sbKdiOS7O9kD9krxPsK8I85A9um9Tr+9THtXVK7fRKM/Wa46Ysen1OWZBmKKlF96CGhTHQ+Pjm8Xe6uhuoWmJ2WX4plWQ+utE/kBvrJ5TdnKUO4UNgHCB2jY/k4vWM1eNSEQLEZnb7ba/dr70JC5z5BhpRp4NOvsdPu4VKC1WK2MVpGd2jFYNUKDDYY/uNtjQZzdd0KiMTPw+DXVb2B8QY1nYGtzOOZ5ljLJxvcWftY3WdS8v9/Sx9dHM79GNpGTrYBDw9SvG6Me/6vNSqZKcHuF5EtvYW75ac3XnEN4v6pMkrj61uyu0qRDq3gjivfhLK9D2a9xulsvs3eu/aIuDwWWkh78i4oMKYyq2UBh29kl5sc34qOUQhOHwroAc2/e3hLpgghlCdmsLYl7O6KSSSg==^1745041489247; ngetAppId=dZRMlECgRX6QjJnYek1SEhlD2VqSWrchYx670hbEHr_Zs5Ta_69w\u0021-735474581; et_appVIP1=1057115658.17439.0000; TS018d84e5=01d83d9ce78206a02c312d3e325088361666f560be2ac8f71d3d44dc3efb51c9726d32c3e5f6105be3e1cf7bf5d8a2154746d67548; _ga_SHTZYKNHG2=GS1.1.1745039630.1.1.1745041565.0.0.0; bm_s=YAAQN0YDF8upOkeWAQAA5RmVTAPXpsYUmwNnR8QQ+/sonrlAPsrIG6zABEy8N9AuBf8m0RRBzl1Y1NNzCyWFplAwXi3K4B3ap0T6Vsz8EP8b6nt6QeXo4i9q/J9+GL6EgAbLloXlJOOVtVbbQwqZA1dvCdyY+bmMIxqIDvAgCJDHU8+E76BH20oClrACwf9pqH+jF3veP2Fplz/M4DJkb47mJJP5cWyYJKf9hPMnELssWCuueazXn0YSItxCaKkG+aHX2RJ0zUulgLeF9AQLLCUDpSoQpEn6EaYEcOS6U0fVZ1wVVcCQvXVb4k0o6q5ew1n7rT7eVbtvQlL0DDBOmaPv1d/nH2Zhpsh/mB1Zl9Vhfv+QsI0ozE+cnHOpuTgHwBtT1RtMyE9SX3aGLklUhZGZCiYQpsziK06me0UcbGA/3ZTx7xUDd7DHwxVWVY17Ir5vTrnPz+vvFWzLluL31g==; RT="z=1&dm=www.irctc.co.in&si=ea039a6d-d875-467f-addb-848d12641828&ss=m9nrjeng&sl=5&tt=1lay&bcn=%2F%2F684d0d49.akstat.io%2F&ld=13vjz&nu=9y8m6cy&cl=17qzq"; _abck=D8B6F63CDAF4608955AFCC122AF2B6F6~0~YAAQFkYDFyPJb0qWAQAAR+GWTA2YoS4R1xWT4hyD9Yunw5NqQ2TYrDktxlDEIhKM48V+wICeJN6BH3XKKU7rpRAjWNkrpr5XT+SVroOB2VTWNA30wUvX7P+3aTVinQDUHME9PXRSdV6PiPzvjlC21ZuFSSOIKhKt9J+S4TJ9viywzoSHbRGS8JqOLpnY8wCCollwS3KuhiYsM+30IvHAOtIWt1ogBZbIax/Wem+DT5iuSkGzWAWM55bye85YUFZ0LvRhkmt/cZCXuuAv8hPeO0Fd6w8dDZAU+MkKxAyfiEsfM87AWJxZMAOpjbLf/cC0vDyz2aQfRrNpYD6ISNm+iuP61J87fqhnVA0mYSfmdhmTPRExbBMNR7czwTR6fsyiMzXWMfadE/qe6VJM88z8hQ5hJEMRauAzlxg9360rNMCcBRxgv4hDIdaU3d1D5gX/uc0PZbNFX10pn+tTEzon4eoSd8ynyYmf8CbsAvPLQjKxfFs51hGwzlpu1jNZ4M4GDDgggg/J63t2crAnDgslK0TfHVj3O1ldHVXR5yG0Q51++vG2y8rg50qwjvtH4sBAogcdf+b9N3xOG9DxXBJosWHjyO8LbWf3GYYmmgbX8bgTadfv8dx6Asx5vDRECVbyntpkX9JP16typV6W2m/FLrnwYJI9aLDHJ4AfqHlFjqxQcuHQxvNVa1Y3hd99BlfLE6yeFJUzm2YFas9oseD4WXwqMhVVg4Ub/EysZH1IcHr/e3VKiF1wIaGinJ+C7BIBNZoImLd+koCKvQsAfh9wWeVy5qawreJbRIp0HT7yP7fBTf42LxVzKPjmrkIVdFwJq6+PRzlUN/Bcfi4Nkk3pu8ScR6knrNrLDi44RqN37Cnwf2Pu9I2s3C9RR9M+tzy9/IU=~-1~-1~1745043221; bm_sz=1C014777F8FA015BACD38209C2F65F4C~YAAQFkYDFyTJb0qWAQAAR+GWTBtXbW4Mii6OXAx31IDtlfAb6APPMEu07oSosJyFRpiQk113DUMPmTZjEuwcqFKCxhykjrhIHFLPzYLMXFawJXngQ6s59yEBZut7/rm/w4p2h/yeq50I6efhW9gw+4nATk2T1eyfr+X5FYba4CPS8n11vCIMzONPqyz4TaKIDWk5l1dvdsZpaPueqI1d7DXkn07IlpoNzs+GGTUs42BEc24M+8svtx9+5HB8Fvrxp3HskUhzgnRCq8fpZo6dHKhaOSJEVHnXvORE6uP7AltPzaCJzqPVyWEvvJmU2wHbmZAoPSwTeA21hEYAgbGVggujbwVac4/L+FbSuizJYjr1b1nyVJQXtWt+kRTmhtI1D7hafDl+NsZlScClqRDNaCf1DwYpV8VCpFN4sUIz2LYHVfQrB6c3fu4YzuDH+xY2+TpQ6X+ouDQFQUWrJBiFdGKNyWlCbbEIHbAiW5k=~4340038~4277825; _ga_NFN218243Z=GS1.1.1745039630.1.1.1745041688.0.0.0; _ga_7K0RMWL72E=GS1.1.1745041477.1.1.1745041688.0.0.0' \
  -H 'pragma: no-cache' \
  -H 'priority: i' \
  -H 'referer: https://www.irctc.co.in/nget/payment/bkgPaymentOptions' \
  -H 'sec-ch-ua: "Google Chrome";v="135", "Not-A.Brand";v="8", "Chromium";v="135"' \
  -H 'sec-ch-ua-mobile: ?0' \
  -H 'sec-ch-ua-platform: "Windows"' \
  -H 'sec-fetch-dest: empty' \
  -H 'sec-fetch-mode: no-cors' \
  -H 'sec-fetch-site: same-origin' \
  -H 'user-agent: Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/135.0.0.0 Safari/537.36' ;




curl 'https://securepubads.g.doubleclick.net/gampad/ads?pvsid=632509865837418&correlator=3076995889108648&eid=95353385%2C31091816%2C95355263%2C83321073%2C31086809%2C31061691%2C31061692&output=ldjh&gdfp_req=1&vrg=202504160101&ptt=17&impl=fifs&iu_parts=37179215%2CGPT_NWEB_PAYMENT_TOP%2CGPT_NWEB_PAYMENT_BOTTOM%2CGPT_NWEB_PAYMENT_RIGHT&enc_prev_ius=%2F0%2F1%2C%2F0%2F2%2C%2F0%2F3&prev_iu_szs=970x90%2C970x90%7C728x90%2C300x250&ifi=27&didk=3952167498~3913621034~3913640691&dids=div-gpt-ad-509525-0~div-gpt-ad-509526-0~div-gpt-ad-509527-0&adfs=2348855042~3903103299~90117463&sfv=1-0-41&sc=1&cookie_enabled=1&abxe=1&dt=1745041804826&lmt=1744719295&adxs=-12245933%2C-12245933%2C-12245933&adys=-12245933%2C-12245933%2C-12245933&biw=1203&bih=912&scr_x=0&scr_y=125&btvi=-1%7C-1%7C-1&ucis=r%7Cs%7Ct&oid=2&u_his=41&u_h=864&u_w=1536&u_ah=816&u_aw=1536&u_cd=24&u_sd=1&u_tz=330&dmc=8&bc=31&nvt=1&uach=WyJXaW5kb3dzIiwiMTkuMC4wIiwieDg2IiwiIiwiMTM1LjAuNzA0OS45NiIsbnVsbCwwLG51bGwsIjY0IixbWyJHb29nbGUgQ2hyb21lIiwiMTM1LjAuNzA0OS45NiJdLFsiTm90LUEuQnJhbmQiLCI4LjAuMC4wIl0sWyJDaHJvbWl1bSIsIjEzNS4wLjcwNDkuOTYiXV0sMF0.&uas=3&url=https%3A%2F%2Fwww.irctc.co.in%2Fnget%2Fpayment%2FbkgPaymentOptions&ref=https%3A%2F%2Fwww.irctc.co.in%2Fnget%2Ferror&rumc=632509865837418&rume=1&vis=1&psz=1203x90%7C872x30%7C270x0&msz=0x0%7C0x0%7C0x0&fws=128%2C128%2C128&ohw=0%2C0%2C0&topics=3&tps=3&htps=10&nt=1&psd=WzMxLFtdLG51bGwsM10.&dlt=1745041486247&idt=1661&prev_scp=Destination%3DPNBE%26Quota%3DTQ%26Departure%3D20042025%26Meal%3D0%26Gender%3DM%26TrainType%3DO%26Arrival%3D21042025%26Age%3D66%26Source%3DKYN%26Classes%3D3E%7CDestination%3DPNBE%26Quota%3DTQ%26Departure%3D20042025%26Meal%3D0%26Gender%3DM%26TrainType%3DO%26Arrival%3D21042025%26Age%3D66%26Source%3DKYN%26Classes%3D3E%7CDestination%3DPNBE%26Quota%3DTQ%26Departure%3D20042025%26Meal%3D0%26Gender%3DM%26TrainType%3DO%26Arrival%3D21042025%26Age%3D66%26Source%3DKYN%26Classes%3D3E&adks=662072717%2C1311454010%2C2906787601&frm=20&eoidce=1&td=1&egid=16524&tan=6156e5d4-379d-4b6e-8367-3ad443808caa%2C6156e5d4-379d-4b6e-8367-3ad443808cab%2C6156e5d4-379d-4b6e-8367-3ad443808cac&tdf=2' \
  -H 'sec-ch-ua-platform: "Windows"' \
  -H 'Referer: https://www.irctc.co.in/' \
  -H 'User-Agent: Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/135.0.0.0 Safari/537.36' \
  -H 'Accept: */*' \
  -H 'sec-ch-ua: "Google Chrome";v="135", "Not-A.Brand";v="8", "Chromium";v="135"' \
  -H 'sec-ch-ua-mobile: ?0' ;




curl 'https://www.irctc.co.in/nget/assets/images/Irctc%20Wallet.PNG' \
  -H 'sec-ch-ua-platform: "Windows"' \
  -H 'Referer: https://www.irctc.co.in/nget/payment/bkgPaymentOptions' \
  -H 'User-Agent: Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/135.0.0.0 Safari/537.36' \
  -H 'sec-ch-ua: "Google Chrome";v="135", "Not-A.Brand";v="8", "Chromium";v="135"' \
  -H 'sec-ch-ua-mobile: ?0' ;




curl 'https://www.irctc.co.in/nget/assets/images/multiplepaymenticon.png' \
  -H 'sec-ch-ua-platform: "Windows"' \
  -H 'Referer: https://www.irctc.co.in/nget/payment/bkgPaymentOptions' \
  -H 'User-Agent: Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/135.0.0.0 Safari/537.36' \
  -H 'sec-ch-ua: "Google Chrome";v="135", "Not-A.Brand";v="8", "Chromium";v="135"' \
  -H 'sec-ch-ua-mobile: ?0' ;




curl 'https://www.irctc.co.in/nget/assets/images/Netbankingicon.png' \
  -H 'sec-ch-ua-platform: "Windows"' \
  -H 'Referer: https://www.irctc.co.in/nget/payment/bkgPaymentOptions' \
  -H 'User-Agent: Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/135.0.0.0 Safari/537.36' \
  -H 'sec-ch-ua: "Google Chrome";v="135", "Not-A.Brand";v="8", "Chromium";v="135"' \
  -H 'sec-ch-ua-mobile: ?0' ;




curl 'https://www.irctc.co.in/nget/assets/images/creditcardicon.png' \
  -H 'sec-ch-ua-platform: "Windows"' \
  -H 'Referer: https://www.irctc.co.in/nget/payment/bkgPaymentOptions' \
  -H 'User-Agent: Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/135.0.0.0 Safari/537.36' \
  -H 'sec-ch-ua: "Google Chrome";v="135", "Not-A.Brand";v="8", "Chromium";v="135"' \
  -H 'sec-ch-ua-mobile: ?0' ;




curl 'https://www.irctc.co.in/nget/assets/images/wallaeticon.png' \
  -H 'sec-ch-ua-platform: "Windows"' \
  -H 'Referer: https://www.irctc.co.in/nget/payment/bkgPaymentOptions' \
  -H 'User-Agent: Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/135.0.0.0 Safari/537.36' \
  -H 'sec-ch-ua: "Google Chrome";v="135", "Not-A.Brand";v="8", "Chromium";v="135"' \
  -H 'sec-ch-ua-mobile: ?0' ;




curl 'https://www.irctc.co.in/nget/assets/images/emi.png' \
  -H 'sec-ch-ua-platform: "Windows"' \
  -H 'Referer: https://www.irctc.co.in/nget/payment/bkgPaymentOptions' \
  -H 'User-Agent: Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/135.0.0.0 Safari/537.36' \
  -H 'sec-ch-ua: "Google Chrome";v="135", "Not-A.Brand";v="8", "Chromium";v="135"' \
  -H 'sec-ch-ua-mobile: ?0' ;




curl 'https://www.irctc.co.in/nget/assets/images/ic_launcher_xxxxx.png' \
  -H 'sec-ch-ua-platform: "Windows"' \
  -H 'Referer: https://www.irctc.co.in/nget/payment/bkgPaymentOptions' \
  -H 'User-Agent: Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/135.0.0.0 Safari/537.36' \
  -H 'sec-ch-ua: "Google Chrome";v="135", "Not-A.Brand";v="8", "Chromium";v="135"' \
  -H 'sec-ch-ua-mobile: ?0' ;




curl 'https://securepubads.g.doubleclick.net/gampad/ads?pvsid=632509865837418&correlator=3076995889108648&eid=95353385%2C31091816%2C95355263%2C83321073%2C31086809%2C31061691%2C31061692&output=ldjh&gdfp_req=1&vrg=202504160101&ptt=17&impl=fifs&iu_parts=37179215%2CGPT_NWEB_PAYMENT_TOP%2CGPT_NWEB_PAYMENT_BOTTOM%2CGPT_NWEB_PAYMENT_RIGHT&enc_prev_ius=%2F0%2F1%2C%2F0%2F2%2C%2F0%2F3&prev_iu_szs=970x90%2C970x90%7C728x90%2C300x250&ifi=27&didk=3952167498~3913621034~3913640691&dids=div-gpt-ad-509525-0~div-gpt-ad-509526-0~div-gpt-ad-509527-0&adfs=2348855042~3903103299~90117463&sfv=1-0-41&sc=1&cookie_enabled=1&abxe=1&dt=1745041804826&lmt=1744719295&adxs=-12245933%2C-12245933%2C-12245933&adys=-12245933%2C-12245933%2C-12245933&biw=1203&bih=912&scr_x=0&scr_y=125&btvi=-1%7C-1%7C-1&ucis=r%7Cs%7Ct&oid=2&u_his=41&u_h=864&u_w=1536&u_ah=816&u_aw=1536&u_cd=24&u_sd=1&u_tz=330&dmc=8&bc=31&nvt=1&uach=WyJXaW5kb3dzIiwiMTkuMC4wIiwieDg2IiwiIiwiMTM1LjAuNzA0OS45NiIsbnVsbCwwLG51bGwsIjY0IixbWyJHb29nbGUgQ2hyb21lIiwiMTM1LjAuNzA0OS45NiJdLFsiTm90LUEuQnJhbmQiLCI4LjAuMC4wIl0sWyJDaHJvbWl1bSIsIjEzNS4wLjcwNDkuOTYiXV0sMF0.&uas=3&url=https%3A%2F%2Fwww.irctc.co.in%2Fnget%2Fpayment%2FbkgPaymentOptions&ref=https%3A%2F%2Fwww.irctc.co.in%2Fnget%2Ferror&rumc=632509865837418&rume=1&vis=1&psz=1203x90%7C872x30%7C270x0&msz=0x0%7C0x0%7C0x0&fws=128%2C128%2C128&ohw=0%2C0%2C0&topics=3&tps=3&htps=10&nt=1&psd=WzMxLFtdLG51bGwsM10.&dlt=1745041486247&idt=1661&prev_scp=Destination%3DPNBE%26Quota%3DTQ%26Departure%3D20042025%26Meal%3D0%26Gender%3DM%26TrainType%3DO%26Arrival%3D21042025%26Age%3D66%26Source%3DKYN%26Classes%3D3E%7CDestination%3DPNBE%26Quota%3DTQ%26Departure%3D20042025%26Meal%3D0%26Gender%3DM%26TrainType%3DO%26Arrival%3D21042025%26Age%3D66%26Source%3DKYN%26Classes%3D3E%7CDestination%3DPNBE%26Quota%3DTQ%26Departure%3D20042025%26Meal%3D0%26Gender%3DM%26TrainType%3DO%26Arrival%3D21042025%26Age%3D66%26Source%3DKYN%26Classes%3D3E&adks=662072717%2C1311454010%2C2906787601&frm=20&eoidce=1&td=1&egid=16524&tan=6156e5d4-379d-4b6e-8367-3ad443808caa%2C6156e5d4-379d-4b6e-8367-3ad443808cab%2C6156e5d4-379d-4b6e-8367-3ad443808cac&tdf=2' \
  -H 'sec-ch-ua-platform: "Windows"' \
  -H 'Referer: https://www.irctc.co.in/' \
  -H 'User-Agent: Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/135.0.0.0 Safari/537.36' \
  -H 'sec-ch-ua: "Google Chrome";v="135", "Not-A.Brand";v="8", "Chromium";v="135"' \
  -H 'sec-ch-ua-mobile: ?0' ;




curl 'https://www.irctc.co.in/nget/assets/images/payment/113.png' \
  -H 'sec-ch-ua-platform: "Windows"' \
  -H 'Referer: https://www.irctc.co.in/nget/payment/bkgPaymentOptions' \
  -H 'User-Agent: Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/135.0.0.0 Safari/537.36' \
  -H 'sec-ch-ua: "Google Chrome";v="135", "Not-A.Brand";v="8", "Chromium";v="135"' \
  -H 'sec-ch-ua-mobile: ?0' ;




curl 'https://www.irctc.co.in/nget/assets/images/safe.png' \
  -H 'sec-ch-ua-platform: "Windows"' \
  -H 'Referer: https://www.irctc.co.in/nget/payment/bkgPaymentOptions' \
  -H 'User-Agent: Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/135.0.0.0 Safari/537.36' \
  -H 'sec-ch-ua: "Google Chrome";v="135", "Not-A.Brand";v="8", "Chromium";v="135"' \
  -H 'sec-ch-ua-mobile: ?0' ;




curl 'https://www.google-analytics.com/g/collect?v=2&tid=G-NFN218243Z&gtm=45je54g3v872522363za200zb9117897900&_p=1745041486402&gcd=13l3l3l3l1l1&npa=0&dma=0&tag_exp=102803279~102813109~102887800~102926062~103027016~103051953~103055465~103077950~103106314~103106316&cid=1504996631.1745039630&ul=en-us&sr=1536x864&uaa=x86&uab=64&uafvl=Google%2520Chrome%3B135.0.7049.96%7CNot-A.Brand%3B8.0.0.0%7CChromium%3B135.0.7049.96&uamb=0&uam=&uap=Windows&uapv=19.0.0&uaw=0&are=1&frm=0&pscdl=noapi&_eu=AEAAAAI&_s=8&dl=https%3A%2F%2Fwww.irctc.co.in%2Fnget%2Fpayment%2FbkgPaymentOptions&dr=https%3A%2F%2Fwww.irctc.co.in%2Fnget%2Fbooking%2FreviewBooking&sid=1745039630&sct=1&seg=1&dt=IRCTC%20Next%20Generation%20eTicketing%20System&en=page_view&_et=17260&tfd=324661' \
  -X 'POST' \
  -H 'accept: */*' \
  -H 'accept-language: en-US,en;q=0.9,de;q=0.8,zh-CN;q=0.7,zh;q=0.6' \
  -H 'cache-control: no-cache' \
  -H 'content-length: 0' \
  -b 'ar_debug=1' \
  -H 'origin: https://www.irctc.co.in' \
  -H 'pragma: no-cache' \
  -H 'priority: u=1, i' \
  -H 'referer: https://www.irctc.co.in/' \
  -H 'sec-ch-ua: "Google Chrome";v="135", "Not-A.Brand";v="8", "Chromium";v="135"' \
  -H 'sec-ch-ua-mobile: ?0' \
  -H 'sec-ch-ua-platform: "Windows"' \
  -H 'sec-fetch-dest: empty' \
  -H 'sec-fetch-mode: no-cors' \
  -H 'sec-fetch-site: cross-site' \
  -H 'sec-fetch-storage-access: active' \
  -H 'user-agent: Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/135.0.0.0 Safari/537.36' ;




curl 'https://www.google-analytics.com/g/collect?v=2&tid=G-NFN218243Z&gtm=45je54g3v872522363za200zb9117897900&_p=1745041486402&gcd=13l3l3l3l1l1&npa=0&dma=0&tag_exp=102803279~102813109~102887800~102926062~103027016~103051953~103055465~103077950~103106314~103106316&cid=1504996631.1745039630&ul=en-us&sr=1536x864&uaa=x86&uab=64&uafvl=Google%2520Chrome%3B135.0.7049.96%7CNot-A.Brand%3B8.0.0.0%7CChromium%3B135.0.7049.96&uamb=0&uam=&uap=Windows&uapv=19.0.0&uaw=0&are=1&frm=0&pscdl=noapi&_eu=AEAAAAI&_s=8&dl=https%3A%2F%2Fwww.irctc.co.in%2Fnget%2Fpayment%2FbkgPaymentOptions&dr=https%3A%2F%2Fwww.irctc.co.in%2Fnget%2Fbooking%2FreviewBooking&sid=1745039630&sct=1&seg=1&dt=IRCTC%20Next%20Generation%20eTicketing%20System&en=page_view&_et=17260&tfd=324661' \
  -X 'POST' \
  -H 'sec-ch-ua-platform: "Windows"' \
  -H 'Referer: https://www.irctc.co.in/' \
  -H 'User-Agent: Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/135.0.0.0 Safari/537.36' \
  -H 'sec-ch-ua: "Google Chrome";v="135", "Not-A.Brand";v="8", "Chromium";v="135"' \
  -H 'sec-ch-ua-mobile: ?0' ;




curl 'https://www.google-analytics.com/g/collect?v=2&tid=G-7K0RMWL72E&gtm=45je54g3v9116751228za200&_p=1745041486402&gcd=13l3l3l3l1l1&npa=0&dma=0&tag_exp=102803279~102813109~102887800~102926062~103027016~103051953~103055465~103077950~103106314~103106316&cid=1504996631.1745039630&ul=en-us&sr=1536x864&uaa=x86&uab=64&uafvl=Google%2520Chrome%3B135.0.7049.96%7CNot-A.Brand%3B8.0.0.0%7CChromium%3B135.0.7049.96&uamb=0&uam=&uap=Windows&uapv=19.0.0&uaw=0&are=1&frm=0&pscdl=noapi&_eu=AEAIAAI&_s=9&dl=https%3A%2F%2Fwww.irctc.co.in%2Fnget%2Fpayment%2FbkgPaymentOptions&dr=https%3A%2F%2Fwww.irctc.co.in%2Fnget%2Fbooking%2FreviewBooking&sid=1745041477&sct=1&seg=1&dt=IRCTC%20Next%20Generation%20eTicketing%20System&en=page_view&_et=17264&tfd=324676' \
  -X 'POST' \
  -H 'sec-ch-ua-platform: "Windows"' \
  -H 'Referer: https://www.irctc.co.in/' \
  -H 'User-Agent: Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/135.0.0.0 Safari/537.36' \
  -H 'sec-ch-ua: "Google Chrome";v="135", "Not-A.Brand";v="8", "Chromium";v="135"' \
  -H 'sec-ch-ua-mobile: ?0' ;




curl 'https://www.google-analytics.com/g/collect?v=2&tid=G-7K0RMWL72E&gtm=45je54g3v9116751228za200&_p=1745041486402&gcd=13l3l3l3l1l1&npa=0&dma=0&tag_exp=102803279~102813109~102887800~102926062~103027016~103051953~103055465~103077950~103106314~103106316&cid=1504996631.1745039630&ul=en-us&sr=1536x864&uaa=x86&uab=64&uafvl=Google%2520Chrome%3B135.0.7049.96%7CNot-A.Brand%3B8.0.0.0%7CChromium%3B135.0.7049.96&uamb=0&uam=&uap=Windows&uapv=19.0.0&uaw=0&are=1&frm=0&pscdl=noapi&_eu=AEAIAAI&_s=9&dl=https%3A%2F%2Fwww.irctc.co.in%2Fnget%2Fpayment%2FbkgPaymentOptions&dr=https%3A%2F%2Fwww.irctc.co.in%2Fnget%2Fbooking%2FreviewBooking&sid=1745041477&sct=1&seg=1&dt=IRCTC%20Next%20Generation%20eTicketing%20System&en=page_view&_et=17264&tfd=324676' \
  -X 'POST' \
  -H 'accept: */*' \
  -H 'accept-language: en-US,en;q=0.9,de;q=0.8,zh-CN;q=0.7,zh;q=0.6' \
  -H 'cache-control: no-cache' \
  -H 'content-length: 0' \
  -b 'ar_debug=1' \
  -H 'origin: https://www.irctc.co.in' \
  -H 'pragma: no-cache' \
  -H 'priority: u=1, i' \
  -H 'referer: https://www.irctc.co.in/' \
  -H 'sec-ch-ua: "Google Chrome";v="135", "Not-A.Brand";v="8", "Chromium";v="135"' \
  -H 'sec-ch-ua-mobile: ?0' \
  -H 'sec-ch-ua-platform: "Windows"' \
  -H 'sec-fetch-dest: empty' \
  -H 'sec-fetch-mode: no-cors' \
  -H 'sec-fetch-site: cross-site' \
  -H 'sec-fetch-storage-access: active' \
  -H 'user-agent: Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/135.0.0.0 Safari/537.36' ;




curl 'https://c.go-mpulse.net/api/config.json?key=UVZSJ-KU924-2H9DH-RYWGJ-FPEZN&d=www.irctc.co.in&t=5816806&v=1.815.70&sl=1&si=ea039a6d-d875-467f-addb-848d12641828-suy970&r=&bcn=%2F%2F684d0d49.akstat.io%2F&acao=&ak.ai=822482' \
  -H 'sec-ch-ua-platform: "Windows"' \
  -H 'Referer: https://www.irctc.co.in/' \
  -H 'User-Agent: Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/135.0.0.0 Safari/537.36' \
  -H 'sec-ch-ua: "Google Chrome";v="135", "Not-A.Brand";v="8", "Chromium";v="135"' \
  -H 'sec-ch-ua-mobile: ?0' ;




curl 'https://c.go-mpulse.net/api/config.json?key=UVZSJ-KU924-2H9DH-RYWGJ-FPEZN&d=www.irctc.co.in&t=5816806&v=1.815.70&sl=1&si=ea039a6d-d875-467f-addb-848d12641828-suy970&r=&bcn=%2F%2F684d0d49.akstat.io%2F&acao=&ak.ai=822482' \
  -H 'accept: */*' \
  -H 'accept-language: en-US,en;q=0.9,de;q=0.8,zh-CN;q=0.7,zh;q=0.6' \
  -H 'cache-control: no-cache' \
  -H 'origin: https://www.irctc.co.in' \
  -H 'pragma: no-cache' \
  -H 'priority: u=1, i' \
  -H 'referer: https://www.irctc.co.in/' \
  -H 'sec-ch-ua: "Google Chrome";v="135", "Not-A.Brand";v="8", "Chromium";v="135"' \
  -H 'sec-ch-ua-mobile: ?0' \
  -H 'sec-ch-ua-platform: "Windows"' \
  -H 'sec-fetch-dest: empty' \
  -H 'sec-fetch-mode: cors' \
  -H 'sec-fetch-site: cross-site' \
  -H 'user-agent: Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/135.0.0.0 Safari/537.36' ;




curl 'https://www.irctc.co.in/nget/assets/images/payment/21.png' \
  -H 'accept: */*' \
  -H 'accept-language: en-US,en;q=0.9,de;q=0.8,zh-CN;q=0.7,zh;q=0.6' \
  -H 'cache-control: no-cache' \
  -b $'bm_ss=ab8e18ef4e; _gid=GA1.3.848614353.1745039630; _gcl_au=1.1.62160036.1745041395; _ga_R24JMMNBXX=GS1.1.1745041395.1.0.1745041395.60.0.0; bm_so=BAD45DE45A27169F689873389A1A82BB7952586A65292A3EAE54527244F77F26~YAAQNUYDF1s0uCKWAQAAZ9CTTAOZm709KRc4fkcke198+g+g1PSx8UnGUu+G9fHsf16sbKdiOS7O9kD9krxPsK8I85A9um9Tr+9THtXVK7fRKM/Wa46Ysen1OWZBmKKlF96CGhTHQ+Pjm8Xe6uhuoWmJ2WX4plWQ+utE/kBvrJ5TdnKUO4UNgHCB2jY/k4vWM1eNSEQLEZnb7ba/dr70JC5z5BhpRp4NOvsdPu4VKC1WK2MVpGd2jFYNUKDDYY/uNtjQZzdd0KiMTPw+DXVb2B8QY1nYGtzOOZ5ljLJxvcWftY3WdS8v9/Sx9dHM79GNpGTrYBDw9SvG6Me/6vNSqZKcHuF5EtvYW75ac3XnEN4v6pMkrj61uyu0qRDq3gjivfhLK9D2a9xulsvs3eu/aIuDwWWkh78i4oMKYyq2UBh29kl5sc34qOUQhOHwroAc2/e3hLpgghlCdmsLYl7O6KSSSg==; _ga=GA1.1.1504996631.1745039630; _ga_JSTMKS9Y3J=GS1.1.1745039631.1.1.1745041488.0.0.0; bm_lso=BAD45DE45A27169F689873389A1A82BB7952586A65292A3EAE54527244F77F26~YAAQNUYDF1s0uCKWAQAAZ9CTTAOZm709KRc4fkcke198+g+g1PSx8UnGUu+G9fHsf16sbKdiOS7O9kD9krxPsK8I85A9um9Tr+9THtXVK7fRKM/Wa46Ysen1OWZBmKKlF96CGhTHQ+Pjm8Xe6uhuoWmJ2WX4plWQ+utE/kBvrJ5TdnKUO4UNgHCB2jY/k4vWM1eNSEQLEZnb7ba/dr70JC5z5BhpRp4NOvsdPu4VKC1WK2MVpGd2jFYNUKDDYY/uNtjQZzdd0KiMTPw+DXVb2B8QY1nYGtzOOZ5ljLJxvcWftY3WdS8v9/Sx9dHM79GNpGTrYBDw9SvG6Me/6vNSqZKcHuF5EtvYW75ac3XnEN4v6pMkrj61uyu0qRDq3gjivfhLK9D2a9xulsvs3eu/aIuDwWWkh78i4oMKYyq2UBh29kl5sc34qOUQhOHwroAc2/e3hLpgghlCdmsLYl7O6KSSSg==^1745041489247; ngetAppId=dZRMlECgRX6QjJnYek1SEhlD2VqSWrchYx670hbEHr_Zs5Ta_69w\u0021-735474581; et_appVIP1=1057115658.17439.0000; TS018d84e5=01d83d9ce78206a02c312d3e325088361666f560be2ac8f71d3d44dc3efb51c9726d32c3e5f6105be3e1cf7bf5d8a2154746d67548; _ga_SHTZYKNHG2=GS1.1.1745039630.1.1.1745041565.0.0.0; bm_s=YAAQN0YDF8upOkeWAQAA5RmVTAPXpsYUmwNnR8QQ+/sonrlAPsrIG6zABEy8N9AuBf8m0RRBzl1Y1NNzCyWFplAwXi3K4B3ap0T6Vsz8EP8b6nt6QeXo4i9q/J9+GL6EgAbLloXlJOOVtVbbQwqZA1dvCdyY+bmMIxqIDvAgCJDHU8+E76BH20oClrACwf9pqH+jF3veP2Fplz/M4DJkb47mJJP5cWyYJKf9hPMnELssWCuueazXn0YSItxCaKkG+aHX2RJ0zUulgLeF9AQLLCUDpSoQpEn6EaYEcOS6U0fVZ1wVVcCQvXVb4k0o6q5ew1n7rT7eVbtvQlL0DDBOmaPv1d/nH2Zhpsh/mB1Zl9Vhfv+QsI0ozE+cnHOpuTgHwBtT1RtMyE9SX3aGLklUhZGZCiYQpsziK06me0UcbGA/3ZTx7xUDd7DHwxVWVY17Ir5vTrnPz+vvFWzLluL31g==; _abck=D8B6F63CDAF4608955AFCC122AF2B6F6~0~YAAQFkYDFyPJb0qWAQAAR+GWTA2YoS4R1xWT4hyD9Yunw5NqQ2TYrDktxlDEIhKM48V+wICeJN6BH3XKKU7rpRAjWNkrpr5XT+SVroOB2VTWNA30wUvX7P+3aTVinQDUHME9PXRSdV6PiPzvjlC21ZuFSSOIKhKt9J+S4TJ9viywzoSHbRGS8JqOLpnY8wCCollwS3KuhiYsM+30IvHAOtIWt1ogBZbIax/Wem+DT5iuSkGzWAWM55bye85YUFZ0LvRhkmt/cZCXuuAv8hPeO0Fd6w8dDZAU+MkKxAyfiEsfM87AWJxZMAOpjbLf/cC0vDyz2aQfRrNpYD6ISNm+iuP61J87fqhnVA0mYSfmdhmTPRExbBMNR7czwTR6fsyiMzXWMfadE/qe6VJM88z8hQ5hJEMRauAzlxg9360rNMCcBRxgv4hDIdaU3d1D5gX/uc0PZbNFX10pn+tTEzon4eoSd8ynyYmf8CbsAvPLQjKxfFs51hGwzlpu1jNZ4M4GDDgggg/J63t2crAnDgslK0TfHVj3O1ldHVXR5yG0Q51++vG2y8rg50qwjvtH4sBAogcdf+b9N3xOG9DxXBJosWHjyO8LbWf3GYYmmgbX8bgTadfv8dx6Asx5vDRECVbyntpkX9JP16typV6W2m/FLrnwYJI9aLDHJ4AfqHlFjqxQcuHQxvNVa1Y3hd99BlfLE6yeFJUzm2YFas9oseD4WXwqMhVVg4Ub/EysZH1IcHr/e3VKiF1wIaGinJ+C7BIBNZoImLd+koCKvQsAfh9wWeVy5qawreJbRIp0HT7yP7fBTf42LxVzKPjmrkIVdFwJq6+PRzlUN/Bcfi4Nkk3pu8ScR6knrNrLDi44RqN37Cnwf2Pu9I2s3C9RR9M+tzy9/IU=~-1~-1~1745043221; bm_sz=1C014777F8FA015BACD38209C2F65F4C~YAAQFkYDFyTJb0qWAQAAR+GWTBtXbW4Mii6OXAx31IDtlfAb6APPMEu07oSosJyFRpiQk113DUMPmTZjEuwcqFKCxhykjrhIHFLPzYLMXFawJXngQ6s59yEBZut7/rm/w4p2h/yeq50I6efhW9gw+4nATk2T1eyfr+X5FYba4CPS8n11vCIMzONPqyz4TaKIDWk5l1dvdsZpaPueqI1d7DXkn07IlpoNzs+GGTUs42BEc24M+8svtx9+5HB8Fvrxp3HskUhzgnRCq8fpZo6dHKhaOSJEVHnXvORE6uP7AltPzaCJzqPVyWEvvJmU2wHbmZAoPSwTeA21hEYAgbGVggujbwVac4/L+FbSuizJYjr1b1nyVJQXtWt+kRTmhtI1D7hafDl+NsZlScClqRDNaCf1DwYpV8VCpFN4sUIz2LYHVfQrB6c3fu4YzuDH+xY2+TpQ6X+ouDQFQUWrJBiFdGKNyWlCbbEIHbAiW5k=~4340038~4277825; _ga_NFN218243Z=GS1.1.1745039630.1.1.1745041805.0.0.0; _ga_7K0RMWL72E=GS1.1.1745041477.1.1.1745041805.0.0.0; RT="z=1&dm=www.irctc.co.in&si=ea039a6d-d875-467f-addb-848d12641828&ss=m9nrjeng&sl=5&tt=1lay&bcn=%2F%2F684d0d49.akstat.io%2F"' \
  -H 'pragma: no-cache' \
  -H 'priority: u=1, i' \
  -H 'referer: https://www.irctc.co.in/nget/ngsw-worker.js' \
  -H 'sec-fetch-dest: empty' \
  -H 'sec-fetch-mode: cors' \
  -H 'sec-fetch-site: same-origin' \
  -H 'user-agent: Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/135.0.0.0 Safari/537.36' ;




curl 'https://www.irctc.co.in/nget/assets/images/payment/21.png' \
  -H 'sec-ch-ua-platform: "Windows"' \
  -H 'Referer: https://www.irctc.co.in/nget/payment/bkgPaymentOptions' \
  -H 'User-Agent: Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/135.0.0.0 Safari/537.36' \
  -H 'sec-ch-ua: "Google Chrome";v="135", "Not-A.Brand";v="8", "Chromium";v="135"' \
  -H 'sec-ch-ua-mobile: ?0' ;




curl 'https://www.irctc.co.in/nget/assets/images/payment/27.png' \
  -H 'sec-ch-ua-platform: "Windows"' \
  -H 'Referer: https://www.irctc.co.in/nget/payment/bkgPaymentOptions' \
  -H 'User-Agent: Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/135.0.0.0 Safari/537.36' \
  -H 'sec-ch-ua: "Google Chrome";v="135", "Not-A.Brand";v="8", "Chromium";v="135"' \
  -H 'sec-ch-ua-mobile: ?0' ;




curl 'https://www.irctc.co.in/nget/assets/images/payment/89.png' \
  -H 'sec-ch-ua-platform: "Windows"' \
  -H 'Referer: https://www.irctc.co.in/nget/payment/bkgPaymentOptions' \
  -H 'User-Agent: Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/135.0.0.0 Safari/537.36' \
  -H 'sec-ch-ua: "Google Chrome";v="135", "Not-A.Brand";v="8", "Chromium";v="135"' \
  -H 'sec-ch-ua-mobile: ?0' ;




curl 'https://www.irctc.co.in/nget/assets/images/payment/115.png' \
  -H 'sec-ch-ua-platform: "Windows"' \
  -H 'Referer: https://www.irctc.co.in/nget/payment/bkgPaymentOptions' \
  -H 'User-Agent: Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/135.0.0.0 Safari/537.36' \
  -H 'sec-ch-ua: "Google Chrome";v="135", "Not-A.Brand";v="8", "Chromium";v="135"' \
  -H 'sec-ch-ua-mobile: ?0' ;




curl 'https://www.irctc.co.in/nget/assets/images/payment/129.png' \
  -H 'sec-ch-ua-platform: "Windows"' \
  -H 'Referer: https://www.irctc.co.in/nget/payment/bkgPaymentOptions' \
  -H 'User-Agent: Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/135.0.0.0 Safari/537.36' \
  -H 'sec-ch-ua: "Google Chrome";v="135", "Not-A.Brand";v="8", "Chromium";v="135"' \
  -H 'sec-ch-ua-mobile: ?0' ;




curl 'https://www.irctc.co.in/nget/assets/images/payment/27.png' \
  -H 'accept: */*' \
  -H 'accept-language: en-US,en;q=0.9,de;q=0.8,zh-CN;q=0.7,zh;q=0.6' \
  -H 'cache-control: no-cache' \
  -b $'bm_ss=ab8e18ef4e; _gid=GA1.3.848614353.1745039630; _gcl_au=1.1.62160036.1745041395; _ga_R24JMMNBXX=GS1.1.1745041395.1.0.1745041395.60.0.0; bm_so=BAD45DE45A27169F689873389A1A82BB7952586A65292A3EAE54527244F77F26~YAAQNUYDF1s0uCKWAQAAZ9CTTAOZm709KRc4fkcke198+g+g1PSx8UnGUu+G9fHsf16sbKdiOS7O9kD9krxPsK8I85A9um9Tr+9THtXVK7fRKM/Wa46Ysen1OWZBmKKlF96CGhTHQ+Pjm8Xe6uhuoWmJ2WX4plWQ+utE/kBvrJ5TdnKUO4UNgHCB2jY/k4vWM1eNSEQLEZnb7ba/dr70JC5z5BhpRp4NOvsdPu4VKC1WK2MVpGd2jFYNUKDDYY/uNtjQZzdd0KiMTPw+DXVb2B8QY1nYGtzOOZ5ljLJxvcWftY3WdS8v9/Sx9dHM79GNpGTrYBDw9SvG6Me/6vNSqZKcHuF5EtvYW75ac3XnEN4v6pMkrj61uyu0qRDq3gjivfhLK9D2a9xulsvs3eu/aIuDwWWkh78i4oMKYyq2UBh29kl5sc34qOUQhOHwroAc2/e3hLpgghlCdmsLYl7O6KSSSg==; _ga=GA1.1.1504996631.1745039630; _ga_JSTMKS9Y3J=GS1.1.1745039631.1.1.1745041488.0.0.0; bm_lso=BAD45DE45A27169F689873389A1A82BB7952586A65292A3EAE54527244F77F26~YAAQNUYDF1s0uCKWAQAAZ9CTTAOZm709KRc4fkcke198+g+g1PSx8UnGUu+G9fHsf16sbKdiOS7O9kD9krxPsK8I85A9um9Tr+9THtXVK7fRKM/Wa46Ysen1OWZBmKKlF96CGhTHQ+Pjm8Xe6uhuoWmJ2WX4plWQ+utE/kBvrJ5TdnKUO4UNgHCB2jY/k4vWM1eNSEQLEZnb7ba/dr70JC5z5BhpRp4NOvsdPu4VKC1WK2MVpGd2jFYNUKDDYY/uNtjQZzdd0KiMTPw+DXVb2B8QY1nYGtzOOZ5ljLJxvcWftY3WdS8v9/Sx9dHM79GNpGTrYBDw9SvG6Me/6vNSqZKcHuF5EtvYW75ac3XnEN4v6pMkrj61uyu0qRDq3gjivfhLK9D2a9xulsvs3eu/aIuDwWWkh78i4oMKYyq2UBh29kl5sc34qOUQhOHwroAc2/e3hLpgghlCdmsLYl7O6KSSSg==^1745041489247; ngetAppId=dZRMlECgRX6QjJnYek1SEhlD2VqSWrchYx670hbEHr_Zs5Ta_69w\u0021-735474581; et_appVIP1=1057115658.17439.0000; TS018d84e5=01d83d9ce78206a02c312d3e325088361666f560be2ac8f71d3d44dc3efb51c9726d32c3e5f6105be3e1cf7bf5d8a2154746d67548; _ga_SHTZYKNHG2=GS1.1.1745039630.1.1.1745041565.0.0.0; bm_s=YAAQN0YDF8upOkeWAQAA5RmVTAPXpsYUmwNnR8QQ+/sonrlAPsrIG6zABEy8N9AuBf8m0RRBzl1Y1NNzCyWFplAwXi3K4B3ap0T6Vsz8EP8b6nt6QeXo4i9q/J9+GL6EgAbLloXlJOOVtVbbQwqZA1dvCdyY+bmMIxqIDvAgCJDHU8+E76BH20oClrACwf9pqH+jF3veP2Fplz/M4DJkb47mJJP5cWyYJKf9hPMnELssWCuueazXn0YSItxCaKkG+aHX2RJ0zUulgLeF9AQLLCUDpSoQpEn6EaYEcOS6U0fVZ1wVVcCQvXVb4k0o6q5ew1n7rT7eVbtvQlL0DDBOmaPv1d/nH2Zhpsh/mB1Zl9Vhfv+QsI0ozE+cnHOpuTgHwBtT1RtMyE9SX3aGLklUhZGZCiYQpsziK06me0UcbGA/3ZTx7xUDd7DHwxVWVY17Ir5vTrnPz+vvFWzLluL31g==; _abck=D8B6F63CDAF4608955AFCC122AF2B6F6~0~YAAQFkYDFyPJb0qWAQAAR+GWTA2YoS4R1xWT4hyD9Yunw5NqQ2TYrDktxlDEIhKM48V+wICeJN6BH3XKKU7rpRAjWNkrpr5XT+SVroOB2VTWNA30wUvX7P+3aTVinQDUHME9PXRSdV6PiPzvjlC21ZuFSSOIKhKt9J+S4TJ9viywzoSHbRGS8JqOLpnY8wCCollwS3KuhiYsM+30IvHAOtIWt1ogBZbIax/Wem+DT5iuSkGzWAWM55bye85YUFZ0LvRhkmt/cZCXuuAv8hPeO0Fd6w8dDZAU+MkKxAyfiEsfM87AWJxZMAOpjbLf/cC0vDyz2aQfRrNpYD6ISNm+iuP61J87fqhnVA0mYSfmdhmTPRExbBMNR7czwTR6fsyiMzXWMfadE/qe6VJM88z8hQ5hJEMRauAzlxg9360rNMCcBRxgv4hDIdaU3d1D5gX/uc0PZbNFX10pn+tTEzon4eoSd8ynyYmf8CbsAvPLQjKxfFs51hGwzlpu1jNZ4M4GDDgggg/J63t2crAnDgslK0TfHVj3O1ldHVXR5yG0Q51++vG2y8rg50qwjvtH4sBAogcdf+b9N3xOG9DxXBJosWHjyO8LbWf3GYYmmgbX8bgTadfv8dx6Asx5vDRECVbyntpkX9JP16typV6W2m/FLrnwYJI9aLDHJ4AfqHlFjqxQcuHQxvNVa1Y3hd99BlfLE6yeFJUzm2YFas9oseD4WXwqMhVVg4Ub/EysZH1IcHr/e3VKiF1wIaGinJ+C7BIBNZoImLd+koCKvQsAfh9wWeVy5qawreJbRIp0HT7yP7fBTf42LxVzKPjmrkIVdFwJq6+PRzlUN/Bcfi4Nkk3pu8ScR6knrNrLDi44RqN37Cnwf2Pu9I2s3C9RR9M+tzy9/IU=~-1~-1~1745043221; bm_sz=1C014777F8FA015BACD38209C2F65F4C~YAAQFkYDFyTJb0qWAQAAR+GWTBtXbW4Mii6OXAx31IDtlfAb6APPMEu07oSosJyFRpiQk113DUMPmTZjEuwcqFKCxhykjrhIHFLPzYLMXFawJXngQ6s59yEBZut7/rm/w4p2h/yeq50I6efhW9gw+4nATk2T1eyfr+X5FYba4CPS8n11vCIMzONPqyz4TaKIDWk5l1dvdsZpaPueqI1d7DXkn07IlpoNzs+GGTUs42BEc24M+8svtx9+5HB8Fvrxp3HskUhzgnRCq8fpZo6dHKhaOSJEVHnXvORE6uP7AltPzaCJzqPVyWEvvJmU2wHbmZAoPSwTeA21hEYAgbGVggujbwVac4/L+FbSuizJYjr1b1nyVJQXtWt+kRTmhtI1D7hafDl+NsZlScClqRDNaCf1DwYpV8VCpFN4sUIz2LYHVfQrB6c3fu4YzuDH+xY2+TpQ6X+ouDQFQUWrJBiFdGKNyWlCbbEIHbAiW5k=~4340038~4277825; _ga_NFN218243Z=GS1.1.1745039630.1.1.1745041805.0.0.0; _ga_7K0RMWL72E=GS1.1.1745041477.1.1.1745041805.0.0.0; RT="z=1&dm=www.irctc.co.in&si=ea039a6d-d875-467f-addb-848d12641828&ss=m9nrjeng&sl=5&tt=1lay&bcn=%2F%2F684d0d49.akstat.io%2F"' \
  -H 'pragma: no-cache' \
  -H 'priority: u=1, i' \
  -H 'referer: https://www.irctc.co.in/nget/ngsw-worker.js' \
  -H 'sec-fetch-dest: empty' \
  -H 'sec-fetch-mode: cors' \
  -H 'sec-fetch-site: same-origin' \
  -H 'user-agent: Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/135.0.0.0 Safari/537.36' ;




curl 'https://www.irctc.co.in/nget/assets/images/payment/89.png' \
  -H 'accept: */*' \
  -H 'accept-language: en-US,en;q=0.9,de;q=0.8,zh-CN;q=0.7,zh;q=0.6' \
  -H 'cache-control: no-cache' \
  -b $'bm_ss=ab8e18ef4e; _gid=GA1.3.848614353.1745039630; _gcl_au=1.1.62160036.1745041395; _ga_R24JMMNBXX=GS1.1.1745041395.1.0.1745041395.60.0.0; bm_so=BAD45DE45A27169F689873389A1A82BB7952586A65292A3EAE54527244F77F26~YAAQNUYDF1s0uCKWAQAAZ9CTTAOZm709KRc4fkcke198+g+g1PSx8UnGUu+G9fHsf16sbKdiOS7O9kD9krxPsK8I85A9um9Tr+9THtXVK7fRKM/Wa46Ysen1OWZBmKKlF96CGhTHQ+Pjm8Xe6uhuoWmJ2WX4plWQ+utE/kBvrJ5TdnKUO4UNgHCB2jY/k4vWM1eNSEQLEZnb7ba/dr70JC5z5BhpRp4NOvsdPu4VKC1WK2MVpGd2jFYNUKDDYY/uNtjQZzdd0KiMTPw+DXVb2B8QY1nYGtzOOZ5ljLJxvcWftY3WdS8v9/Sx9dHM79GNpGTrYBDw9SvG6Me/6vNSqZKcHuF5EtvYW75ac3XnEN4v6pMkrj61uyu0qRDq3gjivfhLK9D2a9xulsvs3eu/aIuDwWWkh78i4oMKYyq2UBh29kl5sc34qOUQhOHwroAc2/e3hLpgghlCdmsLYl7O6KSSSg==; _ga=GA1.1.1504996631.1745039630; _ga_JSTMKS9Y3J=GS1.1.1745039631.1.1.1745041488.0.0.0; bm_lso=BAD45DE45A27169F689873389A1A82BB7952586A65292A3EAE54527244F77F26~YAAQNUYDF1s0uCKWAQAAZ9CTTAOZm709KRc4fkcke198+g+g1PSx8UnGUu+G9fHsf16sbKdiOS7O9kD9krxPsK8I85A9um9Tr+9THtXVK7fRKM/Wa46Ysen1OWZBmKKlF96CGhTHQ+Pjm8Xe6uhuoWmJ2WX4plWQ+utE/kBvrJ5TdnKUO4UNgHCB2jY/k4vWM1eNSEQLEZnb7ba/dr70JC5z5BhpRp4NOvsdPu4VKC1WK2MVpGd2jFYNUKDDYY/uNtjQZzdd0KiMTPw+DXVb2B8QY1nYGtzOOZ5ljLJxvcWftY3WdS8v9/Sx9dHM79GNpGTrYBDw9SvG6Me/6vNSqZKcHuF5EtvYW75ac3XnEN4v6pMkrj61uyu0qRDq3gjivfhLK9D2a9xulsvs3eu/aIuDwWWkh78i4oMKYyq2UBh29kl5sc34qOUQhOHwroAc2/e3hLpgghlCdmsLYl7O6KSSSg==^1745041489247; ngetAppId=dZRMlECgRX6QjJnYek1SEhlD2VqSWrchYx670hbEHr_Zs5Ta_69w\u0021-735474581; et_appVIP1=1057115658.17439.0000; TS018d84e5=01d83d9ce78206a02c312d3e325088361666f560be2ac8f71d3d44dc3efb51c9726d32c3e5f6105be3e1cf7bf5d8a2154746d67548; _ga_SHTZYKNHG2=GS1.1.1745039630.1.1.1745041565.0.0.0; bm_s=YAAQN0YDF8upOkeWAQAA5RmVTAPXpsYUmwNnR8QQ+/sonrlAPsrIG6zABEy8N9AuBf8m0RRBzl1Y1NNzCyWFplAwXi3K4B3ap0T6Vsz8EP8b6nt6QeXo4i9q/J9+GL6EgAbLloXlJOOVtVbbQwqZA1dvCdyY+bmMIxqIDvAgCJDHU8+E76BH20oClrACwf9pqH+jF3veP2Fplz/M4DJkb47mJJP5cWyYJKf9hPMnELssWCuueazXn0YSItxCaKkG+aHX2RJ0zUulgLeF9AQLLCUDpSoQpEn6EaYEcOS6U0fVZ1wVVcCQvXVb4k0o6q5ew1n7rT7eVbtvQlL0DDBOmaPv1d/nH2Zhpsh/mB1Zl9Vhfv+QsI0ozE+cnHOpuTgHwBtT1RtMyE9SX3aGLklUhZGZCiYQpsziK06me0UcbGA/3ZTx7xUDd7DHwxVWVY17Ir5vTrnPz+vvFWzLluL31g==; _abck=D8B6F63CDAF4608955AFCC122AF2B6F6~0~YAAQFkYDFyPJb0qWAQAAR+GWTA2YoS4R1xWT4hyD9Yunw5NqQ2TYrDktxlDEIhKM48V+wICeJN6BH3XKKU7rpRAjWNkrpr5XT+SVroOB2VTWNA30wUvX7P+3aTVinQDUHME9PXRSdV6PiPzvjlC21ZuFSSOIKhKt9J+S4TJ9viywzoSHbRGS8JqOLpnY8wCCollwS3KuhiYsM+30IvHAOtIWt1ogBZbIax/Wem+DT5iuSkGzWAWM55bye85YUFZ0LvRhkmt/cZCXuuAv8hPeO0Fd6w8dDZAU+MkKxAyfiEsfM87AWJxZMAOpjbLf/cC0vDyz2aQfRrNpYD6ISNm+iuP61J87fqhnVA0mYSfmdhmTPRExbBMNR7czwTR6fsyiMzXWMfadE/qe6VJM88z8hQ5hJEMRauAzlxg9360rNMCcBRxgv4hDIdaU3d1D5gX/uc0PZbNFX10pn+tTEzon4eoSd8ynyYmf8CbsAvPLQjKxfFs51hGwzlpu1jNZ4M4GDDgggg/J63t2crAnDgslK0TfHVj3O1ldHVXR5yG0Q51++vG2y8rg50qwjvtH4sBAogcdf+b9N3xOG9DxXBJosWHjyO8LbWf3GYYmmgbX8bgTadfv8dx6Asx5vDRECVbyntpkX9JP16typV6W2m/FLrnwYJI9aLDHJ4AfqHlFjqxQcuHQxvNVa1Y3hd99BlfLE6yeFJUzm2YFas9oseD4WXwqMhVVg4Ub/EysZH1IcHr/e3VKiF1wIaGinJ+C7BIBNZoImLd+koCKvQsAfh9wWeVy5qawreJbRIp0HT7yP7fBTf42LxVzKPjmrkIVdFwJq6+PRzlUN/Bcfi4Nkk3pu8ScR6knrNrLDi44RqN37Cnwf2Pu9I2s3C9RR9M+tzy9/IU=~-1~-1~1745043221; bm_sz=1C014777F8FA015BACD38209C2F65F4C~YAAQFkYDFyTJb0qWAQAAR+GWTBtXbW4Mii6OXAx31IDtlfAb6APPMEu07oSosJyFRpiQk113DUMPmTZjEuwcqFKCxhykjrhIHFLPzYLMXFawJXngQ6s59yEBZut7/rm/w4p2h/yeq50I6efhW9gw+4nATk2T1eyfr+X5FYba4CPS8n11vCIMzONPqyz4TaKIDWk5l1dvdsZpaPueqI1d7DXkn07IlpoNzs+GGTUs42BEc24M+8svtx9+5HB8Fvrxp3HskUhzgnRCq8fpZo6dHKhaOSJEVHnXvORE6uP7AltPzaCJzqPVyWEvvJmU2wHbmZAoPSwTeA21hEYAgbGVggujbwVac4/L+FbSuizJYjr1b1nyVJQXtWt+kRTmhtI1D7hafDl+NsZlScClqRDNaCf1DwYpV8VCpFN4sUIz2LYHVfQrB6c3fu4YzuDH+xY2+TpQ6X+ouDQFQUWrJBiFdGKNyWlCbbEIHbAiW5k=~4340038~4277825; _ga_NFN218243Z=GS1.1.1745039630.1.1.1745041805.0.0.0; _ga_7K0RMWL72E=GS1.1.1745041477.1.1.1745041805.0.0.0; RT="z=1&dm=www.irctc.co.in&si=ea039a6d-d875-467f-addb-848d12641828&ss=m9nrjeng&sl=5&tt=1lay&bcn=%2F%2F684d0d49.akstat.io%2F"' \
  -H 'pragma: no-cache' \
  -H 'priority: u=1, i' \
  -H 'referer: https://www.irctc.co.in/nget/ngsw-worker.js' \
  -H 'sec-fetch-dest: empty' \
  -H 'sec-fetch-mode: cors' \
  -H 'sec-fetch-site: same-origin' \
  -H 'user-agent: Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/135.0.0.0 Safari/537.36' ;




curl 'https://www.irctc.co.in/nget/assets/images/payment/115.png' \
  -H 'accept: */*' \
  -H 'accept-language: en-US,en;q=0.9,de;q=0.8,zh-CN;q=0.7,zh;q=0.6' \
  -H 'cache-control: no-cache' \
  -b $'bm_ss=ab8e18ef4e; _gid=GA1.3.848614353.1745039630; _gcl_au=1.1.62160036.1745041395; _ga_R24JMMNBXX=GS1.1.1745041395.1.0.1745041395.60.0.0; bm_so=BAD45DE45A27169F689873389A1A82BB7952586A65292A3EAE54527244F77F26~YAAQNUYDF1s0uCKWAQAAZ9CTTAOZm709KRc4fkcke198+g+g1PSx8UnGUu+G9fHsf16sbKdiOS7O9kD9krxPsK8I85A9um9Tr+9THtXVK7fRKM/Wa46Ysen1OWZBmKKlF96CGhTHQ+Pjm8Xe6uhuoWmJ2WX4plWQ+utE/kBvrJ5TdnKUO4UNgHCB2jY/k4vWM1eNSEQLEZnb7ba/dr70JC5z5BhpRp4NOvsdPu4VKC1WK2MVpGd2jFYNUKDDYY/uNtjQZzdd0KiMTPw+DXVb2B8QY1nYGtzOOZ5ljLJxvcWftY3WdS8v9/Sx9dHM79GNpGTrYBDw9SvG6Me/6vNSqZKcHuF5EtvYW75ac3XnEN4v6pMkrj61uyu0qRDq3gjivfhLK9D2a9xulsvs3eu/aIuDwWWkh78i4oMKYyq2UBh29kl5sc34qOUQhOHwroAc2/e3hLpgghlCdmsLYl7O6KSSSg==; _ga=GA1.1.1504996631.1745039630; _ga_JSTMKS9Y3J=GS1.1.1745039631.1.1.1745041488.0.0.0; bm_lso=BAD45DE45A27169F689873389A1A82BB7952586A65292A3EAE54527244F77F26~YAAQNUYDF1s0uCKWAQAAZ9CTTAOZm709KRc4fkcke198+g+g1PSx8UnGUu+G9fHsf16sbKdiOS7O9kD9krxPsK8I85A9um9Tr+9THtXVK7fRKM/Wa46Ysen1OWZBmKKlF96CGhTHQ+Pjm8Xe6uhuoWmJ2WX4plWQ+utE/kBvrJ5TdnKUO4UNgHCB2jY/k4vWM1eNSEQLEZnb7ba/dr70JC5z5BhpRp4NOvsdPu4VKC1WK2MVpGd2jFYNUKDDYY/uNtjQZzdd0KiMTPw+DXVb2B8QY1nYGtzOOZ5ljLJxvcWftY3WdS8v9/Sx9dHM79GNpGTrYBDw9SvG6Me/6vNSqZKcHuF5EtvYW75ac3XnEN4v6pMkrj61uyu0qRDq3gjivfhLK9D2a9xulsvs3eu/aIuDwWWkh78i4oMKYyq2UBh29kl5sc34qOUQhOHwroAc2/e3hLpgghlCdmsLYl7O6KSSSg==^1745041489247; ngetAppId=dZRMlECgRX6QjJnYek1SEhlD2VqSWrchYx670hbEHr_Zs5Ta_69w\u0021-735474581; et_appVIP1=1057115658.17439.0000; TS018d84e5=01d83d9ce78206a02c312d3e325088361666f560be2ac8f71d3d44dc3efb51c9726d32c3e5f6105be3e1cf7bf5d8a2154746d67548; _ga_SHTZYKNHG2=GS1.1.1745039630.1.1.1745041565.0.0.0; bm_s=YAAQN0YDF8upOkeWAQAA5RmVTAPXpsYUmwNnR8QQ+/sonrlAPsrIG6zABEy8N9AuBf8m0RRBzl1Y1NNzCyWFplAwXi3K4B3ap0T6Vsz8EP8b6nt6QeXo4i9q/J9+GL6EgAbLloXlJOOVtVbbQwqZA1dvCdyY+bmMIxqIDvAgCJDHU8+E76BH20oClrACwf9pqH+jF3veP2Fplz/M4DJkb47mJJP5cWyYJKf9hPMnELssWCuueazXn0YSItxCaKkG+aHX2RJ0zUulgLeF9AQLLCUDpSoQpEn6EaYEcOS6U0fVZ1wVVcCQvXVb4k0o6q5ew1n7rT7eVbtvQlL0DDBOmaPv1d/nH2Zhpsh/mB1Zl9Vhfv+QsI0ozE+cnHOpuTgHwBtT1RtMyE9SX3aGLklUhZGZCiYQpsziK06me0UcbGA/3ZTx7xUDd7DHwxVWVY17Ir5vTrnPz+vvFWzLluL31g==; _abck=D8B6F63CDAF4608955AFCC122AF2B6F6~0~YAAQFkYDFyPJb0qWAQAAR+GWTA2YoS4R1xWT4hyD9Yunw5NqQ2TYrDktxlDEIhKM48V+wICeJN6BH3XKKU7rpRAjWNkrpr5XT+SVroOB2VTWNA30wUvX7P+3aTVinQDUHME9PXRSdV6PiPzvjlC21ZuFSSOIKhKt9J+S4TJ9viywzoSHbRGS8JqOLpnY8wCCollwS3KuhiYsM+30IvHAOtIWt1ogBZbIax/Wem+DT5iuSkGzWAWM55bye85YUFZ0LvRhkmt/cZCXuuAv8hPeO0Fd6w8dDZAU+MkKxAyfiEsfM87AWJxZMAOpjbLf/cC0vDyz2aQfRrNpYD6ISNm+iuP61J87fqhnVA0mYSfmdhmTPRExbBMNR7czwTR6fsyiMzXWMfadE/qe6VJM88z8hQ5hJEMRauAzlxg9360rNMCcBRxgv4hDIdaU3d1D5gX/uc0PZbNFX10pn+tTEzon4eoSd8ynyYmf8CbsAvPLQjKxfFs51hGwzlpu1jNZ4M4GDDgggg/J63t2crAnDgslK0TfHVj3O1ldHVXR5yG0Q51++vG2y8rg50qwjvtH4sBAogcdf+b9N3xOG9DxXBJosWHjyO8LbWf3GYYmmgbX8bgTadfv8dx6Asx5vDRECVbyntpkX9JP16typV6W2m/FLrnwYJI9aLDHJ4AfqHlFjqxQcuHQxvNVa1Y3hd99BlfLE6yeFJUzm2YFas9oseD4WXwqMhVVg4Ub/EysZH1IcHr/e3VKiF1wIaGinJ+C7BIBNZoImLd+koCKvQsAfh9wWeVy5qawreJbRIp0HT7yP7fBTf42LxVzKPjmrkIVdFwJq6+PRzlUN/Bcfi4Nkk3pu8ScR6knrNrLDi44RqN37Cnwf2Pu9I2s3C9RR9M+tzy9/IU=~-1~-1~1745043221; bm_sz=1C014777F8FA015BACD38209C2F65F4C~YAAQFkYDFyTJb0qWAQAAR+GWTBtXbW4Mii6OXAx31IDtlfAb6APPMEu07oSosJyFRpiQk113DUMPmTZjEuwcqFKCxhykjrhIHFLPzYLMXFawJXngQ6s59yEBZut7/rm/w4p2h/yeq50I6efhW9gw+4nATk2T1eyfr+X5FYba4CPS8n11vCIMzONPqyz4TaKIDWk5l1dvdsZpaPueqI1d7DXkn07IlpoNzs+GGTUs42BEc24M+8svtx9+5HB8Fvrxp3HskUhzgnRCq8fpZo6dHKhaOSJEVHnXvORE6uP7AltPzaCJzqPVyWEvvJmU2wHbmZAoPSwTeA21hEYAgbGVggujbwVac4/L+FbSuizJYjr1b1nyVJQXtWt+kRTmhtI1D7hafDl+NsZlScClqRDNaCf1DwYpV8VCpFN4sUIz2LYHVfQrB6c3fu4YzuDH+xY2+TpQ6X+ouDQFQUWrJBiFdGKNyWlCbbEIHbAiW5k=~4340038~4277825; _ga_NFN218243Z=GS1.1.1745039630.1.1.1745041805.0.0.0; _ga_7K0RMWL72E=GS1.1.1745041477.1.1.1745041805.0.0.0; RT="z=1&dm=www.irctc.co.in&si=ea039a6d-d875-467f-addb-848d12641828&ss=m9nrjeng&sl=5&tt=1lay&bcn=%2F%2F684d0d49.akstat.io%2F"' \
  -H 'pragma: no-cache' \
  -H 'priority: u=1, i' \
  -H 'referer: https://www.irctc.co.in/nget/ngsw-worker.js' \
  -H 'sec-fetch-dest: empty' \
  -H 'sec-fetch-mode: cors' \
  -H 'sec-fetch-site: same-origin' \
  -H 'user-agent: Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/135.0.0.0 Safari/537.36' ;




curl 'https://www.irctc.co.in/nget/assets/images/payment/129.png' \
  -H 'accept: */*' \
  -H 'accept-language: en-US,en;q=0.9,de;q=0.8,zh-CN;q=0.7,zh;q=0.6' \
  -H 'cache-control: no-cache' \
  -b $'bm_ss=ab8e18ef4e; _gid=GA1.3.848614353.1745039630; _gcl_au=1.1.62160036.1745041395; _ga_R24JMMNBXX=GS1.1.1745041395.1.0.1745041395.60.0.0; bm_so=BAD45DE45A27169F689873389A1A82BB7952586A65292A3EAE54527244F77F26~YAAQNUYDF1s0uCKWAQAAZ9CTTAOZm709KRc4fkcke198+g+g1PSx8UnGUu+G9fHsf16sbKdiOS7O9kD9krxPsK8I85A9um9Tr+9THtXVK7fRKM/Wa46Ysen1OWZBmKKlF96CGhTHQ+Pjm8Xe6uhuoWmJ2WX4plWQ+utE/kBvrJ5TdnKUO4UNgHCB2jY/k4vWM1eNSEQLEZnb7ba/dr70JC5z5BhpRp4NOvsdPu4VKC1WK2MVpGd2jFYNUKDDYY/uNtjQZzdd0KiMTPw+DXVb2B8QY1nYGtzOOZ5ljLJxvcWftY3WdS8v9/Sx9dHM79GNpGTrYBDw9SvG6Me/6vNSqZKcHuF5EtvYW75ac3XnEN4v6pMkrj61uyu0qRDq3gjivfhLK9D2a9xulsvs3eu/aIuDwWWkh78i4oMKYyq2UBh29kl5sc34qOUQhOHwroAc2/e3hLpgghlCdmsLYl7O6KSSSg==; _ga=GA1.1.1504996631.1745039630; _ga_JSTMKS9Y3J=GS1.1.1745039631.1.1.1745041488.0.0.0; bm_lso=BAD45DE45A27169F689873389A1A82BB7952586A65292A3EAE54527244F77F26~YAAQNUYDF1s0uCKWAQAAZ9CTTAOZm709KRc4fkcke198+g+g1PSx8UnGUu+G9fHsf16sbKdiOS7O9kD9krxPsK8I85A9um9Tr+9THtXVK7fRKM/Wa46Ysen1OWZBmKKlF96CGhTHQ+Pjm8Xe6uhuoWmJ2WX4plWQ+utE/kBvrJ5TdnKUO4UNgHCB2jY/k4vWM1eNSEQLEZnb7ba/dr70JC5z5BhpRp4NOvsdPu4VKC1WK2MVpGd2jFYNUKDDYY/uNtjQZzdd0KiMTPw+DXVb2B8QY1nYGtzOOZ5ljLJxvcWftY3WdS8v9/Sx9dHM79GNpGTrYBDw9SvG6Me/6vNSqZKcHuF5EtvYW75ac3XnEN4v6pMkrj61uyu0qRDq3gjivfhLK9D2a9xulsvs3eu/aIuDwWWkh78i4oMKYyq2UBh29kl5sc34qOUQhOHwroAc2/e3hLpgghlCdmsLYl7O6KSSSg==^1745041489247; ngetAppId=dZRMlECgRX6QjJnYek1SEhlD2VqSWrchYx670hbEHr_Zs5Ta_69w\u0021-735474581; et_appVIP1=1057115658.17439.0000; TS018d84e5=01d83d9ce78206a02c312d3e325088361666f560be2ac8f71d3d44dc3efb51c9726d32c3e5f6105be3e1cf7bf5d8a2154746d67548; _ga_SHTZYKNHG2=GS1.1.1745039630.1.1.1745041565.0.0.0; bm_s=YAAQN0YDF8upOkeWAQAA5RmVTAPXpsYUmwNnR8QQ+/sonrlAPsrIG6zABEy8N9AuBf8m0RRBzl1Y1NNzCyWFplAwXi3K4B3ap0T6Vsz8EP8b6nt6QeXo4i9q/J9+GL6EgAbLloXlJOOVtVbbQwqZA1dvCdyY+bmMIxqIDvAgCJDHU8+E76BH20oClrACwf9pqH+jF3veP2Fplz/M4DJkb47mJJP5cWyYJKf9hPMnELssWCuueazXn0YSItxCaKkG+aHX2RJ0zUulgLeF9AQLLCUDpSoQpEn6EaYEcOS6U0fVZ1wVVcCQvXVb4k0o6q5ew1n7rT7eVbtvQlL0DDBOmaPv1d/nH2Zhpsh/mB1Zl9Vhfv+QsI0ozE+cnHOpuTgHwBtT1RtMyE9SX3aGLklUhZGZCiYQpsziK06me0UcbGA/3ZTx7xUDd7DHwxVWVY17Ir5vTrnPz+vvFWzLluL31g==; _abck=D8B6F63CDAF4608955AFCC122AF2B6F6~0~YAAQFkYDFyPJb0qWAQAAR+GWTA2YoS4R1xWT4hyD9Yunw5NqQ2TYrDktxlDEIhKM48V+wICeJN6BH3XKKU7rpRAjWNkrpr5XT+SVroOB2VTWNA30wUvX7P+3aTVinQDUHME9PXRSdV6PiPzvjlC21ZuFSSOIKhKt9J+S4TJ9viywzoSHbRGS8JqOLpnY8wCCollwS3KuhiYsM+30IvHAOtIWt1ogBZbIax/Wem+DT5iuSkGzWAWM55bye85YUFZ0LvRhkmt/cZCXuuAv8hPeO0Fd6w8dDZAU+MkKxAyfiEsfM87AWJxZMAOpjbLf/cC0vDyz2aQfRrNpYD6ISNm+iuP61J87fqhnVA0mYSfmdhmTPRExbBMNR7czwTR6fsyiMzXWMfadE/qe6VJM88z8hQ5hJEMRauAzlxg9360rNMCcBRxgv4hDIdaU3d1D5gX/uc0PZbNFX10pn+tTEzon4eoSd8ynyYmf8CbsAvPLQjKxfFs51hGwzlpu1jNZ4M4GDDgggg/J63t2crAnDgslK0TfHVj3O1ldHVXR5yG0Q51++vG2y8rg50qwjvtH4sBAogcdf+b9N3xOG9DxXBJosWHjyO8LbWf3GYYmmgbX8bgTadfv8dx6Asx5vDRECVbyntpkX9JP16typV6W2m/FLrnwYJI9aLDHJ4AfqHlFjqxQcuHQxvNVa1Y3hd99BlfLE6yeFJUzm2YFas9oseD4WXwqMhVVg4Ub/EysZH1IcHr/e3VKiF1wIaGinJ+C7BIBNZoImLd+koCKvQsAfh9wWeVy5qawreJbRIp0HT7yP7fBTf42LxVzKPjmrkIVdFwJq6+PRzlUN/Bcfi4Nkk3pu8ScR6knrNrLDi44RqN37Cnwf2Pu9I2s3C9RR9M+tzy9/IU=~-1~-1~1745043221; bm_sz=1C014777F8FA015BACD38209C2F65F4C~YAAQFkYDFyTJb0qWAQAAR+GWTBtXbW4Mii6OXAx31IDtlfAb6APPMEu07oSosJyFRpiQk113DUMPmTZjEuwcqFKCxhykjrhIHFLPzYLMXFawJXngQ6s59yEBZut7/rm/w4p2h/yeq50I6efhW9gw+4nATk2T1eyfr+X5FYba4CPS8n11vCIMzONPqyz4TaKIDWk5l1dvdsZpaPueqI1d7DXkn07IlpoNzs+GGTUs42BEc24M+8svtx9+5HB8Fvrxp3HskUhzgnRCq8fpZo6dHKhaOSJEVHnXvORE6uP7AltPzaCJzqPVyWEvvJmU2wHbmZAoPSwTeA21hEYAgbGVggujbwVac4/L+FbSuizJYjr1b1nyVJQXtWt+kRTmhtI1D7hafDl+NsZlScClqRDNaCf1DwYpV8VCpFN4sUIz2LYHVfQrB6c3fu4YzuDH+xY2+TpQ6X+ouDQFQUWrJBiFdGKNyWlCbbEIHbAiW5k=~4340038~4277825; _ga_NFN218243Z=GS1.1.1745039630.1.1.1745041805.0.0.0; _ga_7K0RMWL72E=GS1.1.1745041477.1.1.1745041805.0.0.0; RT="z=1&dm=www.irctc.co.in&si=ea039a6d-d875-467f-addb-848d12641828&ss=m9nrjeng&sl=5&tt=1lay&bcn=%2F%2F684d0d49.akstat.io%2F"' \
  -H 'pragma: no-cache' \
  -H 'priority: u=1, i' \
  -H 'referer: https://www.irctc.co.in/nget/ngsw-worker.js' \
  -H 'sec-fetch-dest: empty' \
  -H 'sec-fetch-mode: cors' \
  -H 'sec-fetch-site: same-origin' \
  -H 'user-agent: Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/135.0.0.0 Safari/537.36' ;




curl 'https://www.irctc.co.in/nget/assets/images/safe.png' \
  -H 'sec-ch-ua-platform: "Windows"' \
  -H 'Referer: https://www.irctc.co.in/nget/payment/bkgPaymentOptions' \
  -H 'User-Agent: Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/135.0.0.0 Safari/537.36' \
  -H 'sec-ch-ua: "Google Chrome";v="135", "Not-A.Brand";v="8", "Chromium";v="135"' \
  -H 'sec-ch-ua-mobile: ?0' ;




curl 'https://www.irctc.co.in/nget/assets/images/payment/113.png' \
  -H 'sec-ch-ua-platform: "Windows"' \
  -H 'Referer: https://www.irctc.co.in/nget/payment/bkgPaymentOptions' \
  -H 'User-Agent: Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/135.0.0.0 Safari/537.36' \
  -H 'sec-ch-ua: "Google Chrome";v="135", "Not-A.Brand";v="8", "Chromium";v="135"' \
  -H 'sec-ch-ua-mobile: ?0' ;




curl 'https://www.irctc.co.in/nget/assets/images/safe.png' \
  -H 'sec-ch-ua-platform: "Windows"' \
  -H 'Referer: https://www.irctc.co.in/nget/payment/bkgPaymentOptions' \
  -H 'User-Agent: Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/135.0.0.0 Safari/537.36' \
  -H 'sec-ch-ua: "Google Chrome";v="135", "Not-A.Brand";v="8", "Chromium";v="135"' \
  -H 'sec-ch-ua-mobile: ?0'


  </details>



  </details>
