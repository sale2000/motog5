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


