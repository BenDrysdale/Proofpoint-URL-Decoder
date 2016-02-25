# Proofpoint URL Decoder
Decode rewritten proofpoint urls into human readable format.

.PARAMETER url

Switch: Specifies the url to decode.
	
.EXAMPLE

Get-PPDecode -url "https://urldefense.proofpoint.com/v2/url?u=http-3A__www.example.org_url&d=BwdwBAg&c=TIwfCwdwWnrHy3gMA_uzZorHPsT2wfwvKrwfU"

Decodes the url and outputs it as raw text.

.NOTES

The full url must be entered within brackets: 

Get-PPDecode -url "https://urldefense.proofpoint.com/v2/url?u=http-3A__www.example.org_url&d=BwdwBAg&c=TIwfCwdwWnrHy3gMA_uzZorHPsT2wfwvKrwfU"

.LINK

Github repo: https://github.com/BenDrysdale/Proofpoint-URL-Decoder
