# Child Creativity Lab - Waivers
![CCL Logo](https://user-images.githubusercontent.com/45449494/130186262-a0855101-be2f-4cf2-a9fd-2c7ea289b115.png)
#### Child Creativity Lab aims to foster the next generation of critical thinkers, innovators, and leaders through hands-on creativity enhancing exploration. They incorporate creativity into STEM education, making it easier for children to understand and enjoy.

**🌐** [Website](https://childcreativitylab.org) | [Twitter](https://twitter.com/childcreativity) | [Facebook](https://www.facebook.com/childcreativitylab/) | [Instagram](https://www.instagram.com/childcreativitylab/) | [YouTube](https://www.youtube.com/channel/UCgMSq7Xy2oXarbaUBO2cQIA)


![CCL Web Preview](https://user-images.githubusercontent.com/45449494/130186401-0a6fde21-0def-4922-a209-f245d5d2a258.png)


## 🔎 About the Project

*Child Creativity Lab wanted to sell physical learning kits where only the kit owners had access to their custom-made educational videos. Before this project, there was no readily available platform for easily facilitating this access to buyers of these learning kits.*


🆙 We developed a video platform where administrators can upload videos and generate unique codes for each learning kit that is sent to a customer.

[screenshots]


**Tech Stack:**

**🔼 Frontend:** React

**🔽 Backend:** NodeJS + MySQL


## 💻 Development 

### 🔨 Getting Set Up

1. **Clone the project.**
	
	The `--recursive` flag will download both the frontend and backend submodule repos.  
    
    `git clone --recursive git@github.com:ctc-uci/ccl-videos.git`

2. **Install the dependencies.**

	A postinstall script will also run to install dependencies in the submodules.

	`npm install`

3. **Add the `.env` file to `ccl-videos-backend`.**


### 💨 Running the Project

- `npm start` will run the frontend and backend concurrently
- To start the frontend or backend separately, `cd` into its respective directory and use `npm start` there.