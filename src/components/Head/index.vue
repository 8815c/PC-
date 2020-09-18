<template>
    <div class="headNavigation">
        <div class="headNavigationS">
            <div class="rongqi">
               <div class="rongyiT">
                   <div class="logo">
                     M
                   </div>
                   <div class="shousuokuang">
                       <div class="left">
                           <input type="text">
                           <i class="tu1"></i>
                       </div>
                       <div class="right">
                           <div class="right1">
                               <span class="span1">全部商品</span>
                               <span>热销商品</span>
                           </div>
                           <div class="right2">
                               <i class="i1">图标字体1</i>
                               <i>图标字体2</i>
                           </div>
                       </div>
                   </div>
               </div>
            </div>
        </div>
        <div class="headNavigationX">
            <div class="daohangrongqi">
                <ul class="ul">
                    <li>-</li>
                    <li>首页</li>
                    <li>-</li>
                    <li>全部</li>
                    <li>-</li>
                    <li>品牌周边</li>
                    <li>-</li>
                    <li>热销</li>
                    <li>-</li>
                    <li>活动</li>
                    <li>-</li>
                    <li>折扣</li>
                    <li>-</li>
                    <li>体验</li>
                    <li>-</li>
                    <li>后台</li>
                    <li>-</li>
                    <li>留言板</li>
                </ul>
            </div>
        </div>
        <Headd></Headd>
    </div>
</template>
<script>
import Headd from '../Content/index'
export default {
    name:'Head',
    components:{
        Headd
    }
};
</script>
<style lang="less" scoped>
    //头部导航上
    .headNavigation{
        .headNavigationS{
            width: 100%;
            background-color: #020202;
            .rongqi{
                width: 1220px;
                height: 100px;
                background-color: #020202;
                margin: auto;
                position: relative;
                
                .rongyiT{
                    width: 1220px;
                    height: 40px;
                    position: absolute;
                    top: 0;
                    left: 0;
                    right: 0; 
                    bottom: 0; 
                    margin: auto;
                    .logo{
                        width: 40px;
                        height: 40px;
                        float: left;
                        background-color: white;
                        border-radius: 50%;
                        text-align: center;
                        line-height: 40px;
                        font-size: 25px;
                    }
                    .shousuokuang{
                        height: 40px;
                        float: right;
                        .left{
                            width: 350px;
                            height: 40px;
                            float: left;
                            input{
                                width: 350px;
                                height: 36px;
                                border-radius: 5px;
                            }
                        }
                        .right{
                            width: 450px;
                            height: 40px;
                            float: right;
                            .right1{
                                float: left;
                                font-size: 15px;
                                line-height: 40px;
                                color: white;
                                .span1{
                                    margin: 0 50px 0 30px;
                                }
                            }
                            .right2{
                                float: right;
                                font-size: 15px;
                                line-height: 40px;
                                color: white;
                                .i1{
                                    margin-right: 30px;
                                }
                            }
                        }
                    }
                }
            }
        }
    }
    //头部导航下
    .headNavigation{
        .headNavigationX{
            width: 100%;
            height: 90px;
            margin-bottom: 20px;
            .daohangrongqi{
                width: 1220px;
                height: 90px;
                margin: auto;
                line-height: 90px;
                border-bottom: #333 solid;
                .ul{
                    float: left;
                    li{
                        float: left;
                        font-size: 15px;
                        color: #666;
                        margin: 10px;
                    }
                }
            }
        }
    }
</style>
