<div align=left><div>

# OSUIE: Underwater Image Enhancement with One-step Diffusion Model

<div align=left><div>

## Datasets
The real underwater dataset is available on [Baidu Drive](https://pan.baidu.com/s/1RFVnx6stNDMNcEYwgv34hA?pwd=gcd1).

We use a real-world underwater video captured by an underwater camera in Shenzhen, Guangdong Province, China. The underwater video consists of 300 frames and is available on [Google Drive] and [Baidu Drive](https://pan.baidu.com/s/1RFVnx6stNDMNcEYwgv34hA?pwd=gcd1). If you use this underwater video, please cite our [paper].

<div align=left><div>

## Testing
You can download the pretrained models from [Google Drive].

After downloading, extract the pretrained models into the project folder and replace the `checkpoint` folder, then run `test_OUIEDM.py`.  
The code will automatically process all images in your input folder using the pretrained model and save the enhanced results to your output folder. Our method accepts input images with a resolution of 512×512.

To install the required environment, you can use `requirements.txt` with the following command, or configure the environment by yourself.

```python
pip install -r requirements.txt

