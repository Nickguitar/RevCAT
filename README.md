# RevCAT
## OpenCATS &lt;= 0.9.4 RCE  (CVE-2021-41560)

Opencats &lt;= 0.9.4 fails to properly validade file upload, leading to remote code execution.

If your installed version is &lt;= 0.9.4, [apply the patch](https://github.com/opencats/OpenCATS/commit/b1af3bde1f68bec1c703ad66a3e390f15ed8ebe1) asap.

## Usage

```
./RevCAT.sh <target URL>
```

_Note: &lt;target URL> must point to the root path where OpenCATS is installed._

## Screenshots
  
![image](https://user-images.githubusercontent.com/3837916/141119980-85a55fca-7be8-437b-ab7d-8aa8ce4db567.png)
![image](https://user-images.githubusercontent.com/3837916/141120000-9ec84284-f295-4d21-8a63-2555b495d879.png)
