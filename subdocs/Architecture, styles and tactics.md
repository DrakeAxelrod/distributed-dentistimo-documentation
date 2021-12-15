# <center>Team 16</center>

## <center>Architecture, styles and tactics</center>

### <center>Conceptual design</center>


## Architectural styles

- The system will be event driven, using the publish/subscribe model. This means that in short, there will be event producers publishing messages to a topic to which one or mupltiple consumers are subscribed to. These consumers are independent of each other and are only subscribed the necessary topics. A broker is implemented to act as a middle man between the producers and consumers. The broker keeps track of which subsystem is subscribed to what topic. This style is well-suited for a distributed system where multiple subsystems has to process the same event. It also allows for real-time processing and better performance. Horizontal expansion of this system is also easily achived using this style.


### <center>Conceptual design mapping</center>
