<template>
    
    <div>
        <!-- 登入容器 -->
        <div class="ts narrow container">
            
            <br>
            <br>
            
            <!-- 抬頭 -->
            <h1 class="ts center aligned header">
                Welcome back
                <div class="sub header">We are glad to see you back.</div>
            </h1>
            <!-- / 抬頭 -->
            
            
            <!-- 主要片段 -->
            <div class="ts centered segment" style="max-width: 300px">
                
                <!-- 表單 -->
                <form class="ts form">
                
                    <!-- 單個欄位 -->
                    <div class="field">
                        <label>Username</label>
                        <input type="text" placeholder="">
                    </div>
                    <!-- / 單個欄位 -->
                    
                    
                    <!-- 單個欄位 -->
                    <div class="field">
                        <label>Password</label>
                        <input type="password" placeholder="">
                    </div>
                    <!-- / 單個欄位 -->
                    
                    
                    <!-- 登入按鈕 -->
                    <button class="ts positive fluid button" type="button">Sign in</button>
                    <!-- / 登入按鈕 -->
                    
                </form>
                <!-- / 表單 -->
                
            </div>
            <!-- / 主要片段 -->
            
        </div>
        <!-- /登入容器 -->
   </div>
    
</template>

<script>

export default 
{
    beforeCreate()
    {
        document.title = '登入範例 | Tocas UI'
    }
}
</script>