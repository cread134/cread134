# Hi, My name is Olivia Stewart


## 🚀 About Me
I'm a software engineer with a passion for game development and animation.  


## 🔗 Socials
[![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/olivia-stewart-763090267/)


### 🛠 Skills
![C#](https://img.shields.io/badge/C%23-239120?style=for-the-badge&logo=c-sharp&logoColor=white)
![HTML](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-323330?style=for-the-badge&logo=javascript&logoColor=F7DF1E)
![Node](https://img.shields.io/badge/Node%20js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![.Net](https://img.shields.io/badge/.NET-512BD4?style=for-the-badge&logo=dotnet&logoColor=white)
![Unity](https://img.shields.io/badge/Unity-100000?style=for-the-badge&logo=unity&logoColor=white)
![Vue](https://img.shields.io/badge/Vue%20js-35495E?style=for-the-badge&logo=vuedotjs&logoColor=4FC08D)
![Python](https://img.shields.io/badge/Python-FFD43B?style=for-the-badge&logo=python&logoColor=blue)
![Typescript](https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white)

# Console UI Framework
For an assignment we had to create a console app to manage a hospital.
To do this assignment I wrote a framework for reactive, ui with a fluent api which follows an MVC structure.
[Repository link](https://github.com/cread134/HospitalManagementSystem)

In short you can author ui in like so,
```
public class DoctorAppointmentsView : View
{
	public override void BuildView(ViewBuilder viewBuilder)
	{
		viewBuilder
			.AddControl(new PageHeader("DOTNET Hospital Management System", "All Appointments"))
			.AddControl(new OutputBox(string.Empty, "doctor-appointments-outputBox") { Enabled = false })
			.AddControl(new TableView<AppointmentModel>("All Appointments",
				new TableViewColumn<AppointmentModel>(x => x.APT_Doctor.DCT_User.USR_FullName, overrideName: "Doctor"),
				new TableViewColumn<AppointmentModel>(x => x.APT_Patient.PAT_User.USR_FullName, overrideName: "Patient"),
				new TableViewColumn<AppointmentModel>(x => x.APT_Description),
				new TableViewColumn<AppointmentModel>(x => x.APT_AppointmentTime, overrideName: "Appointment Time")));
	}
}

```

# PDT - Playermakers Dev team 2024
# PDT - Playermakers Dev team 2023

This project is to make a game as a team for university. The team is made of 20 developers, from artists to programmers. I was lead programmer and also did art and animation. The game has been released on steam and itch.io

# Realtime XR projects
I have been experimenting with creating custom frameworks for naturalistic and immersive interaction in XR environments.

Initially I create this project.
[Repository link](https://github.com/cread134/VrFramework)

I am further expanding upon what I learnt there with 
[Repository Link](https://github.com/cread134/UVRCore)

# Projects
## Realtime multiplayer game
[Repository link](https://github.com/cread134/Unity-mutiplayer-survival-game)

Over a year I created a fully playable multiplayer survival game in the unity engine. I programmed from scratch all game systems such as player movement, interaction etc. The project uses the Fishnet Library for networking and has steamworks integration. 
