# Smart Sort

A new way to sort waste for customers

*Team: Arthur Cen, Tim Yan, Varun Yalamanchi*

*This is a course project for CMU Course: Design for Smart System(49-733).*

*Update: 2020-01-30*


## Outline
- [Overview](https://github.com/arthur-cen/smartTrashBin#Overview)
- [Model](https://github.com/arthur-cen/smartTrashBin#Model)
- [Design Solution](https://github.com/arthur-cen/smartTrashBin#Design_Solution)

## Problem
Our background research gave us the following findings:

- Humans generate about 2.2 billion tons of waste every year.
- Currently only 10% is recycled, while there is a potential to
recycle 70%.
- Lack of waste sorting is the main cause of not recycling waste,
thus ending in landfills.
- Many people lack the knowledge to classify waste and dump
everything.

## Reasons

The reasons behind the problem might be people pay less attention when it comes to recycling. Not all people have the awareness of recycling. And there is no insentive to do that because recycling cost is high. Products that uses recycled materials cost higher than those not.

## Our vision

### What can we do?

To design a smart system on the customers’ side that can help classify waste.

### What are we doing here?

Use the waste of SUSHIFUKU to do a pilot project.

### Reasons
- Most wastes are valuable.
- Large amount of waste flow.
- Limited categories of wastes.
- Easily accessible
- Models can be scaled to other restaurants.

## Model Solution

We collected around 500 photos of trash and labeled them(Access the data [here](https://github.com/arthur-cen/smartTrashBin/blob/master/data)). Then, we trained an Image Classification model based on ResNet34 on Google CoLab. (Access the notebook [here](https://github.com/arthur-cen/smartTrashBin/blob/master/smart_sort.ipynb)). The model gave us a 96.45% of accuracy rate.

