# ZXingCodeDemo
基于zxing的二维码扫描，速度快，界面美观，可以自定义

使用
```
<com.moral.qrcodelib.view.ZXingView
        android:id="@+id/zxingview"
        android:layout_width="match_parent"
        android:layout_height="0dp"
        android:layout_below="@+id/top"
        android:layout_weight="1"
        app:qrcv_animTime="1000"
        app:qrcv_barCodeTipText="将条码放入框内，即可自动扫描"
        app:qrcv_barcodeRectHeight="140dp"
        app:qrcv_borderColor="@android:color/white"
        app:qrcv_borderSize="1dp"
        app:qrcv_cornerColor="@color/colorPrimaryDark"
        app:qrcv_cornerLength="20dp"
        app:qrcv_cornerSize="3dp"
        app:qrcv_customScanLineDrawable="@mipmap/scan_icon_scanline"
        app:qrcv_isBarcode="false"
        app:qrcv_isCenterVertical="false"
        app:qrcv_isOnlyDecodeScanBoxArea="false"
        app:qrcv_isScanLineReverse="true"
        app:qrcv_isShowDefaultGridScanLineDrawable="false"
        app:qrcv_isShowDefaultScanLineDrawable="true"
        app:qrcv_isShowTipBackground="true"
        app:qrcv_isShowTipTextAsSingleLine="false"
        app:qrcv_isTipTextBelowRect="false"
        app:qrcv_maskColor="#33FFFFFF"
        app:qrcv_qrCodeTipText="将二维码/条码放入框内，即可自动扫描"
        app:qrcv_rectWidth="200dp"
        app:qrcv_scanLineColor="@color/colorPrimaryDark"
        app:qrcv_scanLineMargin="0dp"
        app:qrcv_scanLineSize="0.5dp"
        app:qrcv_tipTextColor="@android:color/white"
        app:qrcv_tipTextSize="12sp"
        app:qrcv_toolbarHeight="16dp"
        app:qrcv_topOffset="90dp" />
```

二维码
![](https://github.com/shuijilove/ZXingCodeDemo/blob/master/screenshot/Screenshot_2017-05-08-13-39-30.png)

条形码
![](https://github.com/shuijilove/ZXingCodeDemo/blob/master/screenshot/Screenshot_2017-05-08-13-39-09.png)
