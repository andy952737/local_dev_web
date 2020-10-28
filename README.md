# web_localhost_dev

# 前端工具
* bootstrap
* jquery
* java script
* css design / rwd 
* canvas
* krpano(VR全景)  
 
# js技巧
* 取值
* jquery處理迴圈與多筆資料
* js控制項應用# local_dev_web

# krpano xml 
```
<krpano>  
		<include url="webvr.xml" />
		<plugin name="WebVR" mobilevr_fake_support="true" />

    <!-- <include url="../krpano-1.20.8/viewer/plugins/webvr.xml" /> -->
      
  	<!-- <scene> -->
	    <image hfov="360.00" vfov="180.000000" voffset="0.00">
	      <sphere url="vr.jpg" />
	    </image>
   	<!-- </scene> -->  

   	<!-- pano 右鍵選單 --> 
    <contextmenu fullscreen="false" versioninfo="false">
			<item name="全螢幕" caption="全螢幕" enabled="true" separate="true" onclick="switch(fullscreen);"/> 
			<item name="Powered by Demo" caption="Powered by Demo" enabled="true" separate="true" onclick="openurl('https://')"/>   
		</contextmenu>
</krpano>
```
