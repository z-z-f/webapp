<template>
  <div class="self">
  	<div class="self-list">
  		<dl>
  			<dt><i class="fa fa-sitemap"></i></dt>
  			<dd>
  				<h2>简单的做一下自我介绍</h2>
  				<p><span>20</span>个人回答了这个问题</p>
  			</dd>
  		</dl>
  		
  	</div>
  </div>
</template>

<script>
export default {
  name: 'self',
  data () {
    return {

    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.self-list dl {
	display: flex;
	padding: 10px;
	border-bottom: 1px solid #ccc;
}
.self-list dl  dt {
	width: 60px;
	border: 1px solid #ccc;
	height: 60px;
	line-height: 60px;
	text-align: center;
}
.self-list dl  dt  i {
	font-size: 24px;
}
.self-list dl  dd {
	padding-left: 10px;
	flex: 1;
}
.self-list dl dd h2{
	font-weight: normal;
	font-size: 16px;
	width: 200px;
	overflow: hidden;
	text-overflow: ellipsis;
	white-space: nowrap;
	padding-top: 5px;
	padding-bottom: 5px;
}
.self-list dl dd p {
	color: #ccc;
}
.self-list dl dd p span {
	color: #123654;
}
</style>
