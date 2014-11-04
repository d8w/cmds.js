##CMDS web app (Beta)
cmds.js is a web app of the collective mind dataset server(CMDS). It integrates nicely with OZONE Widget Framework [(OWF)](http://www.ozoneplatform.org/).

## Accessing the demo website
Step 1. forward port 8443 (Linux/Mac)

```ssh -L8443:compute-0-0.int.autonlab.org:8443 <your_auton_account>@lop1.autonlab.org```

Windows users can use [PuTTY](https://github.com/d8w/cmds.js/wiki#windows).

Step 2. point your browser to [https://localhost:8443/owf](https://localhost:8443/owf), log in with the following credential
```
testAdmin1
password
```
Proceed regardless of the security risk.

## Portal
* [Users] (https://github.com/d8w/cmds.js/wiki)
  * [How to file a bug](https://github.com/d8w/cmds.js/wiki#how-to-file-a-bug)
  * [Requesting a feature] (https://github.com/d8w/cmds.js/wiki#requesting-a-feature)
* [Developers] (https://github.com/d8w/cmds.js/wiki/Development)

## Browser compatibility
* Firefox
* Chrome
* IE 10+

cmds.js may work in older versions of IE but it is not tested.
