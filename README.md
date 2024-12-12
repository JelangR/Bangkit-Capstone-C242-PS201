# Teknisiku - Machine Learning
## Bangkit Capstone Project 2024
Bangkit Capstone Team ID : C242-PS201 <br>
Here is our repository for the Bangkit 2024 Capstone project - Machine Learning.

## Description
Machine Learning models can be used to inform a content-based filtering approach for its recommendation system. This involves analyzing the proximity as well as the rating of each location, providing quality and nearby recommendations according to the user's position. 

## Method
Content-based Recommendation Systems with Neural Networks

## Tools
- Python
- Sklearn
- Math
- TensorFlow
- NumPy
- Pandas
- Matplotlib
- Google Colab
## Dataset
We made the dataset from scratch by specifying the variables manually in Excel. We created 3 datasets, Model Dataset, Service Dataset, and General Solution Dataset. Variables for the Model Dataset are Nama Tempat, Longitude, Latitude, rating. The explanation of each variable is as follows :
- Nama Tempat : Names of laptop/computer repair shops that will be available on the app from the cities of Surabaya, Yogyakarta, and Solo.
- Longitude : The longitude location of each laptop/computer service center.
- Latitude : The latitude location of each laptop/computer service center.
- Rating : Ratings for the service place or technician of the laptop/computer service place from users who have used the service.
[Dataset Model](https://docs.google.com/spreadsheets/d/1wxiVcxTBrXx9ryhlIE481d1_ccXc1eaMt191JTLil7o/edit?gid=1503308781#gid=1503308781)

The variables for the Service Dataset are Nama Tempat, Foto, Deskripsi, Longitude, Latitude, No Telp, Rating, dan Ulasan. The explanation of each variable is as follows :
- Nama Tempat : Names of laptop/computer repair shops that will be available on the app from the cities of Surabaya, Yogyakarta, and Solo.
- Foto : Photos of each laptop/computer service center.
- Deskripsi : Description of each existing laptop/computer service center.
- Longitude : The longitude location of each laptop/computer service center.
- Latitude :  The latitude location of each laptop/computer service center.
- No Telp : Phone number of each existing laptop/computer service center.
- Rating : Ratings for the service place or technician of the laptop/computer service place from users who have used the service.
- Ulasan : Reviews for the service center or technicians of the service center from users who have used the service.
[Dataset Servis](https://docs.google.com/spreadsheets/d/1ZUxRrJ6_YrTMGGre9Z71Ur-j4MyOwVQ_i6tYxxmwJOw/edit?gid=0#gid=0)

The variables for the General Solution Dataset are Masalah and Solusi. The explanation of each variable is as follows:
- Masalah : Common problems that usually occur with laptops/computers.
- Solusi : General solutions / tips to handle every common laptop/computer problem.
[Dataset Solusi Umum](https://docs.google.com/spreadsheets/d/1lh4mUvs-PW-GjYtNCZwxHs4T6g8n9hnglF7CSE8M0hg/edit?gid=0#gid=0)

We use the Model Dataset to build the model, while the Service Dataset and General Solution Dataset will be used by the cloud computing team to create an application database.
## How to Recommend
The machine learning model can provide recommendations to users where the nearest laptop / computer service is and is supported by ratings and reviews. This computer/laptop service place recommendation is for the cities of Surabaya, Yogyakarta, and Solo.

