  ---
title: "超级英雄"
date: 2019-12-04T18:54:01+08:00
draft: true
categories: [生活]
---

> 如果每个人都做点自己觉得正义的事，那么(他/她) 就是我们的超级英雄。

<!--more-->

<style>
.row {
    margin-right: -15px;
    margin-left: -15px;
}
.btn {
    display: inline-block;
    padding: 6px 12px;
    margin-bottom: 0;
    font-size: 14px;
    font-weight: 400;
    line-height: 1.42857143;
    text-align: center;
    white-space: nowrap;
    vertical-align: middle;
    -ms-touch-action: manipulation;
    touch-action: manipulation;
    cursor: pointer;
    -webkit-user-select: none;
    -moz-user-select: none;
    -ms-user-select: none;
    user-select: none;
    background-image: none;
    border: 1px solid transparent;
    border-radius: 4px;
}
.btn-success {
    color: #fff;
    background-color: #5cb85c;
    border-color: #4cae4c;
    }
.btn-warning {
    color: #fff;
    background-color: #f0ad4e;
    border-color: #eea236;
}
.btn-danger {
    color: #fff;
    background-color: #c9302c;
    border-color: #ac2925;
}

#messageBox {
display:none;
border: 0px ;
position: fixed;
top:0;
left: 40%;
}
</style>

 {{% center %}}




<div id="messageBox">
<div class="container-fluid">
<div class="row">
<div class="col-md-12">
<button type="button" class="btn btn-warning">
你是我们的超级英雄 !!!
</button>
</div>
</div>
</div>


</div>

<div class="container-fluid">
<div class="row">
<div class="col-md-12">
<button type="button" class="btn btn-danger">
清扫路边的垃圾  <icon>😢</icon> 
</button>
</div>
</div>
</div>

---- 

<div class="container-fluid">
<div class="row">
<div class="col-md-12">
<button type="button" class="btn btn-danger">
勇敢做某件事  <icon>😢</icon> 
</button>
</div>
</div>
</div>

----- 
<div class="container-fluid">
<div class="row">
<div class="col-md-12">
<button type="button" class="btn btn-danger">
做家庭晚餐  <icon>😢</icon> 
</button>
</div>
</div>
</div>

----- 
<div class="container-fluid">
<div class="row">
<div class="col-md-12">
<button type="button" class="btn btn-danger">
唱动听的歌 <icon>😢</icon> 
</button>
</div>
</div>
</div>

----- 
{{% /center %}}

<script>
$('button').click(function(){
alert("你是我们的超级英雄！！！");
$(this).removeClass("btn-danger").addClass("btn-success");
$(this).children('icon').text(":slight_smile:");
});

</script>
