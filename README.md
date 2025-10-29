# A Little Introduction
This repository contains 3 personal projects: <br>
1 Tank War Game ([demo video](https://youtu.be/3K--jC5hLa4))<br>
2 Instant Messaging System ([demo video](https://youtu.be/nJLmUAOUesg))<br>
3 Restaurant Management System (with MySQL) ([demo video](https://youtu.be/WTV84IA8ELE)).<br>

## How to run everything
It's recommended to have an IDE (Integrated Development Environment) installed first. It's much easier to open the projects in IDE and run as IDE sets up the runtime environment.
### 1 Tank War Game
Navigate to `1 Tank Game/newtankgameproject/` and run `Game.class`.
### 2 Instant Messaging System
Navigate to `2 Instant Message System/`. Run `im_server/IMFrame.java` first. You should see messages printed on the terminal. Then you can run `im_client/IMView.java`. Use the user names and passwords stored in `im_server/Server.java` to log in. You can start several clients to test out the features.

User names and passwords you can use to log in:
```
static {
        validUsers.put("100", new User("100", "123456"));
        validUsers.put("200", new User("200", "000000"));
        validUsers.put("Jack", new User("Jack", "888888"));
        validUsers.put("Hank", new User("Hank", "999999"));
    }

```

### 3 Restaurant Management System (with MySQL)
It's not recommended to try running this, because MySQL needs installing, configurations need setting, tables need creating (you can refer to all the *.class under `3 Restaurant Management System/src/domain/` to create those tables). However, You can check out the demo video to get the idea. 
