# resnet50-LLM-benchmarks
benchmarks of all implementation of resnet50/bert/LLM on EPYC-DGX single node

## Configs

#### CPU

EPYC 7742 64core

#### GPU 

DGX-A100 40GB

#### Memory

0.98TiB

## Results

<table>
<thead>
  <tr>
    <th>model</th>
    <th>dataset-mode</th>
    <th>hardware</th>    
    <th>precision</th>
    <th>other optimization</th>
    <th>code</th>
    <th>result</th>
    <th>comment</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td rowspan="2">resnet50-v1.5-torchvision</td>
    <td rowspan="2">imagenet2012-val</td>
    <td>CPU</td>
    <td>fp32</td>
    <td>/</td>
    <td><a href="https://github.com/shh2000/parallel-tutorial/blob/main/training_basic_model/simple_cases/matmul_full.py">see code</a></td>
    <td>/</td>
    <td>/</td>
  </tr>
  <tr>
    <td>1 GPU</td>
    <td>fp32</td>
    <td>/</td>
    <td><a href="https://github.com/shh2000/parallel-tutorial/blob/main/training_basic_model/simple_cases/matmul_full.py">see code</a></td>
    <td>/</td>
    <td>/</td>
  </tr>
</tbody>
</table>

