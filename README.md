# Lung-Cancer-Classification

## Purpose

This project was done as a part of my internship at NCL, Pune under Dr. Ram Rup Sarkar. 

## Description

The project contains a Data Pipeline to process whole slide images. This can be used to efficiently create tiles of fixed out of whole slide images which can then be fed into machine learning models for various puposes. I have also used HistomicsTK to segment the nuclei of the while slide images, since it is a major differentiating factor betwee cancerous and non-cancerous tissue.

The other file contains the Res-Net Model that I used to classify the tiles created using the data pipeline. Due to limited storage capabilities and lack of server access, I was not able to train the model on more than a few Images, However, the model is scalable and can be improved further if trained with more data. 
