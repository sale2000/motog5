# Change cedric from oreo to nougat



## Download the stock ROM or the files


```bash
adspso.bin  NON-HLOS.bin
```

## Usage

```bash
fastboot flash recovery twrp-3.5.2_9-0-cedric.img
fastboot flash modem NON-HLOS.bin
fastboot flash dsp adspso.bin
fastboot boot twrp-3.5.2_9-0-cedric.img
```

## Step 3

Boot to twrp

Flash self-compiled LineageOS

## See releases for the zip files 

```bash
github-release upload  --user sale2000 --repo motog5 --tag v0.2.0  --name "XT1676_CEDRIC_RETEU_DS_8.1.0_OPPS28.85-13-4_cid50_subsidy-DEFAULT_regulatory-DEFAULT_CFC.xml.zip" --file  XT1676_CEDRIC_RETEU_DS_8.1.0_OPPS28.85-13-4_cid50_subsidy-DEFAULT_regulatory-DEFAULT_CFC.xml.zip
```
