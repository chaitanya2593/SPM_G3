# Analyzing company performance


<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#Usage">Code Usage</a></li>
    <li><a href="#DATA">Data Files</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>
    <li><a href="#acknowledgments">Reference</a></li>    

    
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project

!!!we have to add a project screen short!!!
[![Product Name Screen Shot][product-screenshot]](https://www.frankfurt-school.de/en/home.html)

We are Frankfurt School (FS) students who are currently pursing Masters in Applied Data Science. As part of our Strategy and 
Performance Management we are doing firm benchmark analysis. Basically we are extracting the key information form the 10-k 
fillings and  financial data available at FS digital database. Then as next steps compare with competitors and provide 
possible recommendations to the firm.

<p align="right">(<a href="#readme-top">back to top</a>)</p>



### Built With

* Python
* Google Colab



<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- GETTING STARTED -->
## Getting Started

ngs are in the google drive, Google colab notebooks are used for development. Colab already has 
required data science packages preinstalled and provided the pip (python package installer) commands where it is required.
### Prerequisites

The user should have an google account and access to the google drive as well.

- Create shortcut onto your drive for below drive links
* Drive link for teh 10-k fillings from Bill McDonald
  ```sh
  https://drive.google.com/drive/folders/1tZP9A0hrAj8ptNP3VE9weYZ3WDn9jHic 
  ```

  
### Installation

You can simply go to Google Colab and you can choose 'GitHub' on the box which you can see when you just go to the Colab site and login. Colab will automatically redirect you to github in order to authorize your github account. Then you can choose repository to use at Google Colab!

- Share google drive folders mentioned in the notebooks to the mounting drive before starting executing 
- Please mount the google drive and execute the notebooks cell



<!-- USAGE EXAMPLES -->
## Code Usage  

Overall end-to-end process has been divided into 6 steps. The execution of the files should also be in the same order.
In individual teh required input files are already mentioned in the code comments.

- 1_data_exploration.ipynb 
  - There are close to 13000 company 10-k fillings and since our objective is to perform analysis for one file we have 
   collected the 10-k fillings for target company and also companies which are in the same domain (Eg Energy sector)   
- 2_Extract_10_K_data.ipynb
  - Now we have extracted the 10-k fillings for the selected companies from 2011-2021 
- 3_data_cleaning_sample.ipynb
  - The text files are basically copy of the whole 10-k fillings and the data further preprocessed. After preprocessing we have extracted the frequency counts. 
- 4_calculate_profitability.ipynb
  - Parallely we have extracted the selected companies financial data for the selected companies and calculated the profitability index  
- 5_Restructuring_Analysis.ipynb
  - Finally we have joined the output files from the notebook number 4 & 5. Later identified the restructuring scenarios. 
- 6_classify_company.ipynb
  - In this step we have classified the companies into 4 buckets and tried to identify the significance of the restructuring. 
<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- DATA -->
## Data Files
# To be filled
<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- LICENSE -->
## License

Distributed under the GNU License. See `LICENSE.txt` for more information.

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- CONTACT -->
## Contact

1. Gezhi Cheng, 
2. Haowei Lee, 
3. Ziyi Liu, 
4. VS Chaitanya Madduri

Project Link: [https://github.com/chaitanya2593/SPM_G3](https://github.com/chaitanya2593/SPM_G3)

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- ACKNOWLEDGMENTS -->
## Reference

* [1. Restructuring and resurrection of Zombie firms](https://clsbluesky.law.columbia.edu/2022/08/23/beyond-the-twilight-zone-the-restructuring-and-resurrection-of-zombie-firms/)
* [2. Charah morning star](https://www.morningstar.com/search?query=Charah%20Solutions%20Inc)

<p align="right">(<a href="#readme-top">back to top</a>)</p>


