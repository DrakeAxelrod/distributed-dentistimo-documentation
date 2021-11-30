# Team 16 Project Documentation
## **Abstract** System Design

![Abstract conceptualization of the system](./diagrams/abstract-design.png)

## Management details

## Developers <a name="developers"></a>

- [Drake Axelrod](https://git.chalmers.se/axelrod)
- [Christofer Jidarv](https://git.chalmers.se/Jidarv)
- [Simon Arvidsson](https://git.chalmers.se/simonar)
- [Klara Svensson](https://git.chalmers.se/klarasve)
- [Robin Hansen](https://git.chalmers.se/robinhan)
- [Johan Axell](https://git.chalmers.se/johanaxe)

## Team Resouces <a name="team resources"></a>

- [Trello](https://trello.com/b/Supm1hiE/dit355-group-16)
- [Discord](https://discord.gg/Xd6E9Nr2qP)
- [Gitlab]()
- [Appointment manager](https://git.chalmers.se/courses/dit355/test-teams-formation/team-16/team-16-project-booker)
- [Authenticator](https://git.chalmers.se/courses/dit355/test-teams-formation/team-16/team-16-project-authentication)
- [Frontend](https://git.chalmers.se/courses/dit355/test-teams-formation/team-16/frontend)
- [MQTT](https://git.chalmers.se/courses/dit355/test-teams-formation/team-16/team-16-project)
- [Gateway](https://git.chalmers.se/courses/dit355/test-teams-formation/team-16/team-16-gateway)


## Subsystem #1

- something about it
    - subpoint
    - sub point
- something about it
### user stories / requirements

## MQTT

- We will be using MQTT as our network protocol. This will enable usage of a publish/subscribe model in order to transfer resources between different units. This transmission is utilizing our broker as a middleman to send and receive messages between the different subsystems. These messages are not sent to a specific receiver, instead they are tagged with a topic and a message, and only the subsystems interested, subscribed, to this specific topic will be receiving them.
Using this architecture style will facilitate our ability to be flexible, while also allowing for greater scalability. This is partly because the publish/subscribe model is asynchronous, but also because we are able to add or remove subscribers without much extra programming being needed. 

### user stories / requirements

## Subsystem #3

- something about it
- something about it
### user stories / requirements

## Subsystem #4

- something about it
- something about it
### user stories / requirements

## Subsystem #5

[Requirements](./subdocs/Requirements.md)

[Team Contract](./subdocs/TeamContract.md)
