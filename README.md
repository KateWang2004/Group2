## Dataset
`data_masked.pt`，在kaggle下载并修改代码中的相关路径。

## LMSPS
`https://github.com/JHL-HUST/LMSPS `
按照链接进去配环境，版本彼此兼容就可以了，注意sparse-tools要自己下载编译，然后进入obgn的文件夹，按照readme运行，最终结果保存在`predictions.csv`中。


## RpHGNN
`https://github.com/CrawlScript/RpHGNN`
同理配环境
然后运行`sh scripts/run_Masked.sh`,预测结果保存在`test_y_pred.csv`。

## HGAMLP
在HGAMLP分支中。
切换到分支后，按照README配环境(可以和LMSPS共享一份环境)，随后修改传入参数`num-hops`或者其他相关参数即可获得不同实验结果，最终结果保存在`predictions_{best_val_accuracy}.csv`中。
