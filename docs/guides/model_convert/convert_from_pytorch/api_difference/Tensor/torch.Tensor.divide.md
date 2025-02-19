## [ torch 参数更多 ] torch.Tensor.divide

### [torch.Tensor.divide](https://pytorch.org/docs/stable/generated/torch.Tensor.divide.html#torch-tensor-divide)

```python
torch.Tensor.divide(other, *, rounding_mode=None)
```

### [paddle.Tensor.divide](https://www.paddlepaddle.org.cn/documentation/docs/zh/api/paddle/Tensor_cn.html#divide-y-name-none)

```python
paddle.Tensor.divide(y, name=None)
```

其中 Pytorch 相比 Paddle 支持更多其他参数，具体如下：

### 参数映射

| PyTorch       | PaddlePaddle | 备注                                                                                |
| ------------- | ------------ | ----------------------------------------------------------------------------------- |
| other         | y            | 表示输入的 Tensor ，仅参数名不一致。                                                   |
| rounding_mode | -            | 用于指定在执行截断除法时的舍入模式。可选值为 'floor'(向下取整) 或 'trunc'(截断)。Paddle 无此功能，暂无转写方式。|
