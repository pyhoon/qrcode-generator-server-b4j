# QRCode Generator Server

Can be use with B4JServer, Web API Server and Non-UI app (does not depend on XUI or jFX)

# Usage
```vb
Dim img As String = File.Combine(Main.AssetFolder, "img")
Dim generate As ZXing
generate.Initialize
generate.QrCode(value, 400, File.Combine(img, "image.png"), "png")
```

## Additional Libraries:
[core-3.5.1.jar](https://repo1.maven.org/maven2/com/google/zxing/core/3.5.1/core-3.5.1.jar)

[javase-3.5.1.jar](https://repo1.maven.org/maven2/com/google/zxing/javase/3.5.1/javase-3.5.1.jar)

[jZXing.jar](https://www.b4x.com/android/forum/attachments/jzxing-zip.139610/)

## Preview
<img src="https://github.com/pyhoon/qrcode-generator-server-b4j/raw/main/Preview.png" width="480" title="Preview" />
