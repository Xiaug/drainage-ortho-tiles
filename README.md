# drainage-ortho-tiles

中科二期開發 3D 查詢網頁用的空拍正射影像圖磚。

- 來源：台中F25-1150928-RTK-orthomosaic.tiff（PIX4Dmatic，GSD 10 cm）
- 座標：TWD97 TM2（EPSG:3826），不重投影
- 範圍：3D 查詢網頁國土測繪中心底圖範圍（模型外框 ±200 m）與影像的交集
- 結構：{z}/{x}/{y}.webp，1024 px 圖磚，z=0~4，tiles.json 為索引
