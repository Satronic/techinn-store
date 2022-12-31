# TechInn Store

TechInn Store is a copy of the e-commerce [TechInn](https://www.tradeinn.com/techinn/) e-commerce that was developed with the VTEX IO platform, in order to put into practice the technical concepts of web development seen in the Vtex University bootcamp.

The website is divided into the following semantic sections that allow modularizing its development:

## 1. Header
### 1.1. Header Desktop
![Media Placeholder](https://res.cloudinary.com/satronic/image/upload/v1672447977/Header-Desktop_rncp0l.jpg)

#### 1.1.1. Header Desktop Menu Categories
![Media Placeholder](https://res.cloudinary.com/satronic/image/upload/v1672448210/Header-Desktop-Menu-Categories_mlnc36.jpg)

### 1.2. Header Tablet
![Media Placeholder](https://res.cloudinary.com/satronic/image/upload/v1672447422/Header-Tablet_b8frtb.jpg)

#### 1.2.1. Header Tablet Menu Categories
![Media Placeholder](https://res.cloudinary.com/satronic/image/upload/v1672448855/Header-Tablet-Menu-Categories_bjfelh.jpg)

### 1.3. Header Phone
![Media Placeholder](https://res.cloudinary.com/satronic/image/upload/v1672447715/Header-Phone_bgw7u6.jpg)

#### 1.3.1. Header Phone Menu Categories
![Media Placeholder](https://res.cloudinary.com/satronic/image/upload/v1672448583/Header-Phone-Menu-Categories_j6p9to.jpg)


## 2. Home
### 2.1. Home Desktop Slider Top
![Media Placeholder](https://res.cloudinary.com/satronic/image/upload/v1672509125/Home-Desktop-Slider-Top_asdusa.jpg)

### 2.2. Home Desktop Banners Categories and Brands
![Media Placeholder](https://res.cloudinary.com/satronic/image/upload/v1672509408/Home-Desktop-Banners-Ctegories-Brands_edffre.jpg)

### 2.2. Home Desktop Slider Products and About Us Section
![Media Placeholder](https://res.cloudinary.com/satronic/image/upload/v1672509750/Home-Desktop-Slider-Products_quhfmu.jpg)


## 3. Footer
### 3.1. Footer Desktop
![Media Placeholder](https://res.cloudinary.com/satronic/image/upload/v1672510642/Footer-Desktop_rn1a48.jpg)

### 3.2. Footer Tablet
![Media Placeholder](https://res.cloudinary.com/satronic/image/upload/v1672511069/Footer-Tablet_ntk4s6.jpg)

### 3.3. Footer Phone
![Media Placeholder](https://res.cloudinary.com/satronic/image/upload/v1672511386/Footer-Phone_my8rwb.jpg)


#### 4. Search
#### 5. Product
#### 6. Custom

## A. Configuration

### Step 1 -  Basic setup

Access the VTEX IO [basic setup guide](https://vtex.io/docs/getting-started/build-stores-with-store-framework/1) and follow all the given steps. 

By the end of the setup, you should have the VTEX command line interface (Toolbelt) installed along with a developer workspace you can work in.

### Step 2 - Cloning the Minimum Boilerplate Theme repository

[Clone](https://help.github.com/en/github/creating-cloning-and-archiving-repositories/cloning-a-repository) this repository to your local files to be able to effectively start working on it.

Then, access the repository's directory using your terminal. 

### Step 3 - Editing the `Manifest.json`

Once in the repository directory, it is time to edit the Minimum Boilerplate `manifest.json` file. 

Once you are in the file, you must replace the `vendor` and `account` values. `vendor` is the account name you are working on and `account` is anything you want to name your theme. For example:

```json
{
  "vendor": "storecomponents",
  "name": "my-test-theme",
}
```

### Step 4 -  Installing required apps

In order to use Store Framework and work on your store theme, it is needed to have both `vtex.store-sitemap` and `vtex.store` installed.

Run  `vtex list`  and check whether those apps are already installed. 

If they aren't, run the following command to install them: `vtex install vtex.store-sitemap vtex.store -f`

### Step 5 -  Uninstalling any existing theme

By running `vtex list`,  you can verify if any theme is installed.

It is common to already have a `vtex.store-theme`  installed when you start the store's front development process. 

Therefore, if you find it in the app's list, copy its name and use it together with the command `vtex uninstall`. For example:

```json
vtex uninstall vtex.store-theme
```

### Step 6- Run and preview your store

Then time has come to upload all the changes you made in your local files to the platform. For that, use the `vtex link` command. 

If the process runs without any errors, the following message will be displayed: `App linked successfully`. Then, run the `vtex browse` command to open a browser window having your linked store in it.

This will enable you to see the applied changes in real time, through the account and workspace in which you are working.
