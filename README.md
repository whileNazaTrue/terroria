<h1 align="center">Terroria</h1>
<p align="center">A Terraria Server for Google Colab</p>


## Google Colab

Google Colab is a Google service that allows Python code execution and running it through the browser. It's free to use and, even though it's more designed for tasks such as machine learning, it can be used for our purpose as well.

Even though it's free, it would be better not to abuse the service that's provided, thus being thankful for Google providing this free space for testing applications.

## What will you need.

1. A Google account
2. An account on ngrok.

## How to run

1. Go to [Google Colab](https://colab.research.google.com/)
2. Create a new notebook
3. Paste the code as instructed in the Terroria.ipynb, in the two separate files. Run them in order. The first file will only need to be executed the first time you run the application. After this for running the server you will have to run the second one only when shutdown and turned on again.
4. The console will prompt you to enter a ngrok auth token that you can find [here](https://dashboard.ngrok.com/get-started/your-authtoken).
4.1 It can happen sometimes that you get an error because all the tunnels are occupied and not free. You can go [here](https://dashboard.ngrok.com/tunnels/agents) and end the agents sessions if it happens.
5. The console will print something like this: \n
   ```url: NgrokTunnel: "tcp://4.tcp.ngrok.io:14832" -> "localhost:7777"```

When Terraria asks you the IP, you enter it without the port and the tcp://

![image](https://github.com/whileNazaTrue/terroria/assets/84025828/949af94d-109a-466d-a7ac-a47937827a96)

Leave the port as 7777.

Important notice, this link may change every time the application is changed, given how ngrok works. Make sure you keep track.

5.1 The first time you execute the server you will be prompted to create a new world:

![image](https://github.com/whileNazaTrue/terroria/assets/84025828/3e2b8fda-8687-4416-983b-0e920b125cc6)

Choose the world, or create one and follow the steps. Select the world size and other things as you wish, but don't alter options regarding port/port forwarding, just press Enter and wait for the world to be generated.

## 
After this you will be done and you can join and play with your friends! Have fun!

## Special thanks.

Thanks to [thecoder-001](https://github.com/thecoder-001). They created the code for this to be run on Minecraft. I inspired a big part of their code to make mine into reality, and it served as a guide for me to understand how to make this work.\n

## Contact

If you wish to make improvements, comments, or write something, you can use the issues tab, if you need to talk about some other thing you can include somewhere I can contact you (social media, or maybe an email).


