# <div style="text-align: center;">A Lightweight Deep Learning Framework for Wild Berry Detection in Complex Natural Environments</div>


## Introduction 
WildB-YOLO is an advanced iteration of the YOLOv11n model, featuring several cutting-edge enhancements designed to push the boundaries of object detection. Key innovations include the FrogFPN for multi-scale feature fusion, the SACM module for richer contextual representations, and the Weighted EMA Loss, which effectively addresses class imbalance challenges. Additionally, we employ the LAMP pruning technique to streamline the model, achieving lightweight optimization without compromising detection accuracy. This combination results in a highly efficient model that significantly reduces computational resource demands while maintaining exceptional performance.

### Recommended Environment

Please refer to the official configuration settings of Ultralytics

## WildBerry Dataset
Thanks to the Riz team for providing the dataset, you can download the dataset used for WildB-YOLO training from the following link 
**Hugging Face:** [Wild Berry image dataset collected in Finnish forests and peatlands using drones)](https://huggingface.co/datasets/FBK-TeV/WildBe)
```
@article{riz2024wild,
  title={Wild Berry image dataset collected in Finnish forests and peatlands using drones},
  author={Riz, Luigi and Povoli, Sergio and Caraffa, Andrea and Boscaini, Davide and Mekhalfi, Mohamed Lamine and Chippendale, Paul and Turtiainen, Marjut and Partanen, Birgitta and Ballester, Laura Smith and Noguera, Francisco Blanes and others},
  journal={arXiv preprint arXiv:2405.07550},
  year={2024}
}
```
