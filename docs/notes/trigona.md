# 💰 _Ransom notes for group_ trigona
> 🔗 [trigona](group/trigona)
* **[how_to_decrypt.hta](https://ransomware.live/ransomware_notes/trigona/how_to_decrypt.hta)**

```
ï»¿<!DOCTYPE HTML PUBLIC "-//W3C//DTD HTML 4.01 Transitional//EN" "http://www.w3.org/TR/html4/loose.dtd">
<html>
<title>ENCRYPTED</title>
<hta:application showInTaskBar="no" APPLICATION="yes" ICON='msiexec.exe' SINGLEINSTANCE='yes' SysMenu="no" applicationname="ENCRYPTED" border="thick" contexmenu="no" scroll="no" selection="yes" singleinstance="yes" windowstate="normal" MAXIMIZEBUTTON="NO" BORDER="DIALOG" width="100" height="100" MINIMIZEBUTTON="NO"></hta:application>
<script language="JavaScript">
  var authkey = '';
  var email = 'farusbig@tutanota.com';
  var url = 'http://3x55o3u2b7cjs54eifja5m3ottxntlubhjzt6k6htp5nrocjmsxxh7ad.onion/';
  var vid = '[snip]';
  var cid = '[snip]';
  var uniqueid;

  function Start() {
    window.resizeTo(658,500);
    
    if (vid == '') {
      uniqueid = cid;
    } else {
      uniqueid = vid;
    }
  }
  function copytext(s) {
    window.clipboardData.setData("Text", s);
    alert('Auth Key copied to clipboard');
  };
  function openpage(url) {
    window.clipboardData.setData("Text", url);
    alert('URL copied to buffer. Open it in TOR Browser');
  }
  function help() {
    window.clipboardData.setData("Text", uniqueid);
    alert('If you have trouble with the main contacts, write to '+email+'. Your ID copied to buffer');
  }
  function document.onkeydown() {
    var alt = window.event.altKey;
    if (event.keyCode == 116 || event.keyCode == 27 || alt && event.keyCode == 115) {
      event.keyCode = 0;
      event.cancelBubble = true;
      return false;
    }
  }
  Start();
</script>

<body style="background: #ffffff; font: 12px 'Arial', sans-serif; padding: 0; margin: 0; overflow-x: hidden;" onload="Start();">
<textarea style="display: none" id="authkey">--START_OF_DATA--
[snip]
--END_OF_DATA--</textarea>
<div style="">
  <div style="width: 100%; height: 100%; position: absolute; top: 0; left: 0; box-sizing: border-box; padding: 0px; overflow-x: hidden;overflow-y: hidden; background-color: #ffffff;">
    
<div style="background-color: #A0031D; box-sizing: border-box; width: 100%; padding: 14px 0;">
      <div style="text-align: center; color: #ffffff; font-size: 25px; font-weight: 700; text-transform: uppercase;">the entire network is encrypted <br>your business is losing money</div>
    </div>

    <div style="background-color: #ffffff; width: 600px; padding: 20px; box-sizing: border-box;">
      <div style="margin-right: 18px; float: left; width: 31%;">
        <span style="float: left; font-weight: 700; color: #F80129; margin-right: 2px;">&#9650;</span>
        <div style="float: left; font-size: 12px; color: #000000; width: 170px;">All documents, databases, backups and other critical data were encrypted and leaked</div>
        <div style="clear: both; float: none; height: 18px; width: 100%;"></div>
      </div>

      <div style="margin-right: 18px; float: left; width: 31%;">
        <span style="float: left; font-weight: 700; color: #F80129; margin-right: 2px;">&#9650;</span>
        <div style="float: left; font-size: 12px; color: #000000; width: 170px;">The program uses a secure AES algorithm, which makes decryption impossible without contacting us</div>
        <div style="clear: both; float: none; height: 18px; width: 100%;"></div>
      </div>

      <div style="float: left; width: 31%;">
        <span style="float: left; font-weight: 700; color: #F80129; margin-right: 2px;">&#9650;</span>
        <div style="float: left; font-size: 12px; color: #000000; width: 160px;">If you refuse to negotiate, the data will be auctioned off</div>
        <div style="clear: both; float: none; height: 18px; width: 100%;"></div>
      </div>
      <div style="clear: both; float: none; height: 0px; width: 100%;"></div>

      <div style="border: 1px solid #e5e5e5; padding: 20px; box-sizing: border-box;">
        <div style="font-size: 14px; font-weight: 700; color: #000000; text-align: center;">To recover your data, please follow the instructions</div>

        <div style="margin-top: 10px;">
          <div style="float: left; margin-right: 10px; margin-left: 10px; width: 31%;">
            <div style="font-size: 40px; font-weight: bold; color: #e5e5e5; float: left; margin-right: 13px;">1</div>
            <div style="float: left; margin-top: 5px;">
              <div style="font-size: 12px; color: #5E5C5C; margin-bottom: 3px;">Download Tor Browser</div>
              <a href="https://www.torproject.org/dist/torbrowser/11.5.7/torbrowser-install-win64-11.5.7_en-US.exe" style="font-size: 14px; font-weight: 700; color: #0C94E0; text-decoration: none;" target="_blank">Download</a>
            </div>
            <div style="clear: both; float: none;"></div>
          </div>

          <div style="float: left; margin-right: 10px; margin-left: 10px; width: 31%;">
            <div style="font-size: 40px; font-weight: bold; color: #e5e5e5; float: left; margin-right: 13px;">2</div>
            <div style="float: left; margin-top: 5px;">
              <div style="font-size: 12px; color: #5E5C5C; margin-bottom: 3px;">Open decryption page</div>
              <a href="#" style="font-size: 14px; font-weight: 700; color: #0C94E0; text-decoration: none;" target="_blank" onclick="openpage(url); return false;">Copy</a>
            </div>
            <div style="clear: both; float: none;"></div>
          </div>

          <div style="float: left; margin-right: 10px; margin-left: 10px; width: 31%;">
            <div style="font-size: 40px; font-weight: bold; color: #e5e5e5; float: left; margin-right: 13px;">3</div>
            <div style="float: left; margin-top: 5px;">
              <div style="font-size: 12px; color: #5E5C5C; margin-bottom: 3px;">Auth using this key</div>
              <a href="#" style="font-size: 14px; font-weight: 700; color: #0C94E0; text-decoration: none;" onclick="copytext(authkey); return false;">Copy</a>
            </div>
            <div style="clear: both; float: none;"></div>
          </div>

          <div style="clear: both; float: none;"></div>
        </div>
      </div>

      <div style="margin-top: 18px; width: 100%;">
        <div style="float: left; font-size: 12px; color: #5E5C5C;">The price depends on how soon you will contact us</div>
        <a href="" style="float: right; font-size: 12px; color: #0C94E0; text-decoration: none;" onclick="help(); return false;">Need help?</a>
        <div style="clear: both; float: none;"></div>
      </div>
    </div>

    <div style="padding: 20px 30px; width: 600px; background-color: #f7f2f3; box-sizing: border-box;">
      <div style="float: left; margin-right: 21px;">
        <div style="float: left; font-size: 11px; color: #F80129; font-weight: 700; margin-right: 6px;">â</div>
        <div style="float: left; width: 110px;">
          <div style="font-size: 11px; font-weight: 700; color: #000000; margin-bottom: 2px; margin-top: 1px;">Don't doubt</div>
          <div style="font-size: 11px; color: #5E5C5C;">You can decrypt 3 files for free as a guarantee</div>
        </div>
      </div>

      <div style="float: left; margin-right: 27px;">
        <div style="float: left; font-size: 11px; color: #F80129; font-weight: 700; margin-right: 6px;">â</div>
        <div style="float: left; width: 103px;">
          <div style="font-size: 11px; font-weight: 700; color: #000000; margin-bottom: 2px; margin-top: 1px;">Don't waste time</div>
          <div style="font-size: 11px; color: #5E5C5C;">Decryption price increases every hour</div>
        </div>
      </div>

      <div style="float: left; margin-right: 27px;">
        <div style="float: left; font-size: 11px; color: #F80129; font-weight: 700; margin-right: 6px;">â</div>
        <div style="float: left;  width: 114px;">
          <div style="font-size: 11px; font-weight: 700; color: #000000; margin-bottom: 2px; margin-top: 1px;">Don't contact resellers</div>
          <div style="font-size: 11px; color: #5E5C5C;">They resell our services at a premium</div>
        </div>
      </div>

      <div style="float: left;">
        <div style="float: left; font-size: 11px; color: #F80129; font-weight: 700; margin-right: 6px;">â</div>
        <div style="float: left; width: 108px;">
          <div style="font-size: 11px; font-weight: 700; color: #000000; margin-bottom: 2px; margin-top: 1px;">Don't recover files</div>
          <div style="font-size: 11px; color: #5E5C5C;">Additional recovery software will damage your data</div>
        </div>
      </div>

      <div style="clear: both; float: none; height: 0px; width: 100%;"></div>
    </div>
  </div>
</div>
<script language="JavaScript">
authkey = document.getElementById('authkey').value;
</script>
</body>

</html>

```


> [!TIP]> Ransomware notes are provided by [Zscaler ThreatLabz](https://github.com/threatlabz/ransomware_notes) under MIT License
> 




Last update : _Monday 20/11/2023 16.14 (UTC)_

