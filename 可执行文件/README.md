Step1：下载预训练好的模型放到./model路径下, 以下为我们提供的不同预训练模型的说明及下载地址：

    MSRA: 在MSRA（新闻语料）上训练的模型。[下载地址](https://pan.baidu.com/s/1twci0QVBeWXUg06dK47tiA)

    CTB8: 在CTB8（新闻文本及网络文本的混合型语料）上训练的模型。[下载地址](https://pan.baidu.com/s/1DCjDOxB0HD2NmP9w1jm8MA)

    WEIBO: 在微博（网络文本语料）上训练的模型。[下载地址](https://pan.baidu.com/s/1QHoK2ahpZnNmX6X7Y9iCgQ)


Step2: 运行可执行文件

    window环境运行样例: pkuseg.exe test msr_test.utf8 msr_test_output_soft.utf8
    
    linux环境运行样例：mono pkuseg.exe test msr_test.utf8 msr_test_output.utf8