# 💰 _Ransom notes for group_ donut
> 🔗 [donut](group/donut)
* **[d0nut.html](https://ransomware.live/ransomware_notes/donut/d0nut.html)**

```
<!DOCTYPE html>
<html lang="en"><head><meta charset="UTF-8"><style>
body{
  height: 100vh;
  display: flex;
  align-items: center;
  justify-content: center;
  background-color: black;
}
h1{
  font-family: 'Oswald', sans-serif;
  text-transform: uppercase;
  font-size: 90%;
  text-align: left;
  color: white;
}
span{
  display: inline-block;
}
.container {
        overflow: hidden;
        background-color: black;
        height: 100%;
}
.container {
        color: white;
        display: -webkit-flexbox;
        display: -ms-flexbox;
        display: -webkit-flex;
        display: flex;
        -webkit-flex-align: center;
        -ms-flex-align: center;
        -webkit-align-items: center;
        align-items: center;
        justify-content: center;
}
</style></head>
<body><link href='https://fonts.googleapis.com/css?family=Oswald:300' rel='stylesheet' type='text/css'>
<div class="container"><pre class="center" id="d"></pre></div><script>
var pretag = document.getElementById("d");
var tmr1 = undefined,
  tmr2 = undefined;
var A = 1,
  B = 1;
var asciiframe = () => {
  var b = [];
  var z = [];
  A += 0.07;
  B += 0.03;
  var cA = Math.cos(A),
    sA = Math.sin(A),
    cB = Math.cos(B),
    sB = Math.sin(B);
  for (var k = 0; k < 1760; k++) {
    b[k] = k % 80 == 79 ? "\n" : " ";
    z[k] = 0;
  }
  for (var j = 0; j < 6.28; j += 0.07) {
    var ct = Math.cos(j),
      st = Math.sin(j);
    for (i = 0; i < 6.28; i += 0.02) {
      var sp = Math.sin(i),
        cp = Math.cos(i),
        h = ct + 2, // R1 + R2*cos(theta)
        D = 1 / (sp * h * sA + st * cA + 5),
        t = sp * h * cA - st * sA;
      var x = 0 | (40 + 30 * D * (cp * h * cB - t * sB)),
        y = 0 | (12 + 15 * D * (cp * h * sB + t * cB)),
        o = x + 80 * y,
        N =
          0 |
          (8 *
            ((st * sA - sp * ct * cA) * cB -
              sp * ct * sA -
              st * cA -
              cp * ct * sB));
      if (y < 22 && y >= 0 && x >= 0 && x < 79 && D > z[o]) {
        z[o] = D;
        b[o] = ".,-~:;=!*#$@"[N > 0 ? N : 0];
      }
    }
  }
  pretag.innerHTML = b.join("");
};
setInterval(asciiframe, 50)
</script><h1><pre>
So what happened?

All files are encrypted with Integrated Encryption Scheme.
The file structure was not damaged. You have been assigned a unique identifier.
After infection, you have 96 hours to declare decryption.

After the expiration of 96 hours, decryption cost will be automatically increased.
Now you should send us message with your personal ID, which is at the bottom of the message.
We hope that you understand the importance of the work we have done.

Before paying you can send us 2 files for free decryption.
The total size of files must be less than 2Mb.
Files should not contain valuable information (databases, backups, large excel sheets, etc..).

Attention! If you want to RECOVER YOUR DATA without problems - NEVER!!! :
reboot, disconnect hard drives or take any action unless you know WHAT YOU ARE DOING!!!
Otherwise, we cannot be 100% sure that the decryptor will work correctly.

!!!THIS IS ESPECIALLY RELATED TO ESXI!!!

If you will try to use any third party software for restoring your data or antivirus solutions:
this can lead to complete damage to all files and their irrecoverable loss.
Any changes in encrypted files may entail damage of the private key and the loss of all data.

Your personal id: [snip]
Username and password are identical to above.

Since we are using SSL encryption as well as .onion, the certificate is not properly signed.
So in order to get into the chat, you need to confirm the insecure connection exception.
Or just use our embeded APP (Windows version only for now). Thank you for understanding.

You can download TOX here:
https://tox.chat/download.html

You can also write to the chat located in TOR network at:
https://qkbbaxiuqqcqb5nox4np4qjcniy2q6m7yeluvj7n5i5dn7pgpcwxwfid.onion

You can download TOR browser here:
https://www.torproject.org/download/

our TOX below:
D3404141459BC7206CC4AFEC16A3403F262C0937A732C12644E7CA97F0615201A519F7EAB2E2

We hope you carefully read this message and already know what to do.
</pre></h1></body></html>

```


> [!TIP]> Ransomware notes are provided by [Zscaler ThreatLabz](https://github.com/threatlabz/ransomware_notes) under MIT License
> 




Last update : _Monday 20/11/2023 16.14 (UTC)_

