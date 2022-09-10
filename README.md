# NCNN BREAKDOWN
A breakdown of NCNN

## One

This tutorial is a record of the author's own learning process of ncnn. It is equivalent to writing out my own understanding. If there are any mistakes, please correct me.

This tutorial has not been written yet, and will be updated from time to time as the learning progresses.

## Two

Each section of this tutorial will be divided into 4 sections to describe, namely:

> - **start**　
> - **effect**
> - **accomplish**
> - **code example**

**Start**：At the beginning of each section, talk about the current study plan.

**Role**：Talk about the role of the content to be discussed in this section.

**Implementation**：Tell me how ncnn is implemented in this section.

**Code example**：Take out the ncnn-related code in this section and write an example.

## Three

For each section, for the convenience of presentation, I will use some charts to display, such as:

![lession-5](https://github.com/Zhengtq/ncnn_breakdown/blob/main/image/lession-5.png)

![Mat](https://github.com/Zhengtq/ncnn_breakdown/blob/main/image/Mat.png)

![](https://github.com/Zhengtq/ncnn_breakdown/blob/main/image/tree.png)

| head | pad_x | (head_use)elemsize | elemsize | elemsize | elemsize | pad_y | pad_y... | (x)      |
| :--- | ----- | ------------------ | :------: | -------- | -------- | ----- | -------- | -------- |
| (x)  | (x)   | (channel2)elemsize | elemsize | elemsize | elemsize | pad_y | pad_y... | (x)      |
| (x)  | (x)   | (channel3)elemsize | elemsize | elemsize | elemsize | pad_y | pad_y... | (x)      |
| (x)  | (x)   | (channel4)elemsize | elemsize | elemsize | elemsize | pad_y | pad_y... | pad_z... |

## Four
At the end of each section, I will attach the corresponding sample code. When using the sample code in each section, you need to clone it yourself, and then compile it yourself. A common procedure is as follows:
```bash
git clone git@github.com:Zhengtq/ncnn_breakdown.git
cd ncnn_breakdown && cd lesson && cd lesson_1
mkdir build &&cd build
cmake ..
make -j8
./examples/lession_1
```

## Five

Have Fun !


