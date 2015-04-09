# LoadViewHelper
切换加载中，加载失败，加载成功布局，定义一个LoadViewHelper所有界面通用。
![](https://github.com/longtaoge/LoadViewHelper/blob/master/lodingview.gif)

----------



    LoadViewHelper helper = new LoadViewHelper(listView);  
	  //将listview切换成显示加载中布局  
		helper.showLoading("加载中...");  
		//将listview切换成显示空数据布局
		helper.showEmpty("暂无数据", "重试", new OnClickListener() {  

			@Override  
			public void onClick(View v) {  
  
			}  
		});  



  
Copyright 2014 shizhefei（LuckyJayce）

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

   http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
