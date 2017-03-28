# rn_segmentview
a simple segmentView for react-native  

### usage
Download the `segmentView.js` file and import it into your react-native project when you need it

	<SegmentView dataSource={['1','2','3','4']} 
		type={'plain'} 
		perWidth={40} 
		selectedWithIndex={0} 
		selectedWithIndex={(index)=>{
			console.log("==== select with index ",index);
	}}/>
	

### three types 

- radius 
![radius](https://github.com/yongqianvip/rn_segmentview/blob/master/img/sg_radius.png?raw=true)

- plain  
![](https://github.com/yongqianvip/rn_segmentview/blob/master/img/sg_plain.png?raw=true) 

- radius\_space\_between  
![](https://github.com/yongqianvip/rn_segmentview/blob/master/img/sg_radius_space_between.png?raw=true) 






