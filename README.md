<!--
 * @Descripttion: your project
 * @version: 1.0
 * @Author: luxin
 * @Date: 2024-03-10 21:25:44
 * @LastEditTime: 2024-03-12 11:15:32
-->
# GIDC

Tensorflow implementation of paper: [Far-field super-resolution ghost imaging with a deep neural network constraint.](https://www.nature.com/articles/s41377-021-00680-w). One of the experiment data was provided.

## Citation
Really thanks the author of **GIDC paper：**freely donate the code to the public for the undergraduate student to use.

Fei Wang, Chenglong Wang, Mingliang Chen, Wenlin Gong, Yu Zhang, Shensheng Han and Guohai Situ. Far-field super-resolution ghost imaging with a deep neural network constraint. *Light Sci Appl* **11**, 1 (2022).

## Abstract
Here is the brief abstract for the target paper: Ghost imaging (GI) facilitates image acquisition under low-light conditions by single-pixel measurements and thus has great potential in applications in various fields ranging from biomedical imaging to remote sensing. However, GI usually requires a large amount of single-pixel samplings in order to reconstruct a high-resolution image, imposing a practical limit for its applications. Here we propose a far-field super-resolution GI technique that incorporates the physical model for GI image formation into a deep neural network. The resulting hybrid neural network does not need to pre-train on any dataset, and allows the reconstruction of a far-field image with the resolution beyond the diffraction limit. Furthermore, the physical model imposes a constraint to the network output, making it effectively interpretable. We experimentally demonstrate the proposed GI technique by imaging a flying drone, and show that it outperforms some other widespread GI techniques in terms of both spatial resolution and sampling ratio. We believe that this study provides a new framework for GI, and paves a way for its practical applications.

## Usage
- prepare the correct env and download the data.mat
- transfer the tensorflow to the pytorch framwork and test the data you captured in the ground truth
- prepare the file in the same folder path and get the correct speckel pattern math with the data

## Plan
- prepare the pytorch framwork for the GIDC and test the Imaging quality
- prepare the GAN and the Extension GAN Model to test the Imaging quality
- prepare the Cycle and Dual Network Construction to test the Imaging quality
- use the present model construction to get the present solution to define the quality

## Folder Construction
