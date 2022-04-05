# ZJU-nCov-Hitcarder-Sample

浙大nCov肺炎健康打卡定时自动脚本 

forked from [Tishacy/ZJU-nCov-Hitcarder](https://github.com/Tishacy/ZJU-nCov-Hitcarder)

# Sample .yml

```yml
- name: Working
   uses: Long0x0/zju-ncov-hitcarder@0.0.x
      with:
         # zju account username(student  id).
         username: ${{ secrets.ZJU_USERNAME }}
         # zju account password.
         password: ${{ secrets.ZJU_PASSWORD }}
         # (optional) dingtalk_token.
         dingtalk_token: ${{ secrets.DINGTALK_TOKEN }}
         # (optional) serverchan_key.
         serverchan_key: ${{ secrets.SERVERCHAN_KEY }}
```

# Sample Repository

https://github.com/Long0x0/ZJU-nCov-Hitcarder-Sample

https://oapi.dingtalk.com/robot/send?access_token=e3877ecca0d65c00ea1310df83c5f762041b258a62cdd02c871f8cf28deac733