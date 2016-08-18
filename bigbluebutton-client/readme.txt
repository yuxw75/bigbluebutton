1.bbb-web org.bigbluebutton.modules.videoconf.business.VideoProxy 去掉h264处理 以满足ios播放视频需要
2.bbb-app org.bigbluebutton.view.navigation.pages.common.VideoView 直接播放streamName处理  解决ios不能正常播放的问题
3.bbb-app MenuButtonsViewMediator.as  app传值   app启动app
4.bbb-app LoginPageViewMediator.as    app传值   app启动app


https://github.com/yuxw75/bbb-air-client
https://github.com/yuxw75/bbb-air-client-1.git


-locale zh_CN -locale en_US  -source-path=./locale/{locale} -resource-bundle-list=used-resource-bundles.txt -allow-source-path-overlap=true


bbb-web
ConfigParameters  ConfigManager2   bbbweb修改地址


EnterApiService
"http://112.74.96.171/bigbluebutton/api/enter";


url = "http://112.74.96.171/bigbluebutton/api/join?meetingID=1361469443566213&password=md&fullName=%E4%BD%99%E6%99%93%E6%96%87&logoutURL=http://lwork.hk&checksum=0753029db8c2fc6ed0ff34a9a01565295327a812";
//url = "https://demo.bigbluebutton.org/bigbluebutton/api/join?meetingID=Demo+Meeting&fullName=ssss&password=mp&checksum=54c5a668bc8002c7efc439f15954a7b7bb6b4a6c";
			

			
		