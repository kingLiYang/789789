<template>
    <div>
        <!-- <div>1111</div>  -->
        <!-- <div class="crumbs">
            <el-breadcrumb separator="/">
                <el-breadcrumb-item><i class="el-icon-setting"></i> 首页</el-breadcrumb-item>
            </el-breadcrumb>
        </div> -->
        <!-- <h2 :clas="[classA ? 'classa' : 'classb']">前言</h2>
        <h2 :clas="[classA ? 'classa' : 'classb']">前言</h2>
        <h2 :clas="[classA ? 'classa' : 'classb']">前言</h2>
        <h2 :clas="[classA ? 'classa' : 'classb']">前言</h2>
        <h2 :clas="[classA ? 'classa' : 'classb']">前言</h2>
        <h2 :class="[classA ? 'classa' : 'classb']">前言</h2>
        <h2 :class="[classA ? 'classa' : 'classb']">前言</h2>
        <h2>前言</h2> -->
    </div>
</template>

<script>
export default {
  data: function() {
    return {
        classA: false
    };
  },
  created(){
      if([]){
        //   this.classA = fasle;
      }
  }
};
</script>

<style scoped>
    .classa{
        cursor: pointer;
    }
    .classb{
        cursor: not-allowed;
    }
</style>