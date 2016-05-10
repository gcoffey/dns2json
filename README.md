# dns-lookup-2-json
Prints results of a DNS lookup in pretty json

Simply run...
<pre>
./dns2json www.garethcoffey.com
</pre>

and you'll get a nice JSON object back

<pre>
./dns2json www.garethcoffey.com
{
    "www.garethcoffey.com": {
        "NS": [
            "garethcoffey-main-875502665.eu-west-1.elb.amazonaws.com."
        ]
    }
}
{
    "www.garethcoffey.com": {
        "A": [
            "garethcoffey-main-875502665.eu-west-1.elb.amazonaws.com.",
            "54.154.229.204",
            "54.72.243.206"
        ]
    }
}
{
    "www.garethcoffey.com": {
        "CNAME": [
            "garethcoffey-main-875502665.eu-west-1.elb.amazonaws.com."
        ]
    }
}
</pre>
