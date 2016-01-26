# DNS

For a new domain we set the following DNS entries, here for a domain
`example.com`.

## Host records

<table>
    <tr>
        <th>Record</th>
        <th>Host</th>
        <th>Value</th>
    </tr>
    <tr>
        <td>A record</td>
        <td>@</td>
        <td>[IP of server]</td>
    </tr>
    <tr>
        <td>CNAME record</td>
        <td>autoconfig</td>
        <td>autoconfig.indie.host</td>
    </tr>
    <tr>
        <td>CNAME record</td>
        <td>www</td>
        <td>example.com.</td>
    </tr>
    <tr>
        <td>TXT record</td>
        <td>@</td>
        <td>v=spf1 include:mail.indie.host</td>
    </tr>
    <tr>
        <td>TXT record</td>
        <td>_dmarc</td>
        <td>v=DMARC1; p=none; rua=mailto:support@indie.host</td>
    </tr>
    <tr>
        <td>TXT record</td>
        <td>mail_domainkey</td>
        <td>v=DKIM1; k=rsa; p=[DKIM key]</td>
    </tr>
</table>

## Mail records

<table>
    <tr>
        <th>Record</th>
        <th>Host</th>
        <th>Value</th>
    </tr>
    <tr>
        <td>MX record</td>
        <td>@</td>
        <td>mail.indie.host</td>
    </tr>
</table>

