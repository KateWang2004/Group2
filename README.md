## LMSPS
`https://github.com/JHL-HUST/LMSPS `
按照链接进去配环境，版本彼此兼容就可以了，注意sparse-tools要自己下载编译，然后进入obgn的文件夹，按照readme运行就行了（跳过search阶段），结果会保存在`predictions.csv`中。


## RpHGNN
`https://github.com/CrawlScript/RpHGNN`
同理配环境
然后运行`sh scripts/run_Masked.sh`,预测结果保存在`test_y_pred.csv`。

## 大作业示例代码
RGCN的实现，预测结果保存在`submission.csv`中。
我们的数据是`data_masked.pt`,太大了需要自行去kaggle链接下载，而且我用的是绝对路径,报错的位置你记得改一下路径。