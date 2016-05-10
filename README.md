# dns-lookup-2-json
Print results of a DNS lookup in JSON

<pre>
USAGE: ./dns2json <DNS NAME> <NAMESERVER>(optional)
e.g. ./dns2json www.google.com 8.8.8.8
</pre>

Simply run...
<pre>
./dns2json www.garethcoffey.com
</pre>

and you'll get a nice JSON object back

<pre>
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
