# Cloud Computing

- [Cloud Computing](#cloud-computing)
  - [General](#general)
  - [History of Cloud Computing](#history-of-cloud-computing)
  - [Products](#products)
    - [Containers](#containers)
    - [Processing](#processing)
    - [Scalability](#scalability)
    - [Amazon Web Services](#amazon-web-services)
    - [Google Cloud](#google-cloud)
      - [Getting Started](#getting-started)
        - [Configuring multiple VM's](#configuring-multiple-vms)
    - [Microsoft Azure](#microsoft-azure)
      - [Example](#example)
  - [Other](#other)
    - [Sources](#sources)

Cloud computing is a relatively new field in computer science, yet everything being learned and done with the internet was ultimately leading down to this. This is essentially because using the cloud is like using the internet. People use the cloud nearly every day whether at work or at home saving pictures and documents or even looking at a website, without even realizing. Cloud computing is an important topic in not only computer science but also in distributed systems for many reasons. Cloud computing implements distributed system properties like scalability. In this chapter we will go through the general principles of cloud computing and what can be done with cloud computing. Afterwards, we will discuss popular cloud computing solutions currently being provided by companies like Amazon, Google, and Microsoft. A nice addition is that all three of these comes with free trials so we can learn to use them for free. Lastly, there will be other things related to cloud services briefly to be mention at the end.

![cloud Computing](images/Cloud-Computing-1.jpg "Cloud Computing")[^9]

## General

---

In essence cloud computing is doing exactly what a computer and server does, except the services are on a different network across the internet. These services include but are not limited to processing, storage, software, intelligence, and databases. All this of course is done for a price, since most things unlike this book are not free. Yet even though it is not free that doesn't mean it is a bad thing since it means we are getting a high quality of service. The Cloud is also helpful for businesses since they don't always need to have their own servers to do something or can supplement their own servers further with minimal expansion by paying a company that runs a cloud service to do whatever they need done.[^1]

There are a quite a few advantages to cloud computing:

    -Speed
      - All most immediately services are ready, so whenever we need it, it's there
    - Cost
      - Cloud Computing is a lot cheaper for users and companies then buying and setting up servers and storage
      - We don't have to spend money on electricity to power our own personal servers
    - Scale
      - Completely elastic, so as a company grows its servers can grow in the cloud as needed
    - Productivity
      - We save time setting up the servers, changes are updated rapidly
    - Performance
      - Servers are kept up to date constantly that way the user always gets the best possible service
    - Security
      - Servers are protected by their own security meaning users can spend less resources and money on security

Cloud services achieve these advantages by not only using the latest and best technologies around but by using common distributed system properties. For example, a lot of what is stored in cloud services is put onto multiple servers for data persistency, that way if one server or more servers happen to break, our files and applications will still be available for us and our clients. Additionally, since they use a lot of servers, they can make multiple do a single task like run a program or a website that way it can be used by a lot of users without lagging or crashing. That way if there aren't enough servers, a company or user can easily expand the cloud networks horizontally by adding more servers or processors. Since cloud servers are setup like this we will have fault Tolerance and low latency since things aren't being bottlenecked by a single central server. This fault tolerance and low latency that is built into cloud services means that we as the user will also have a low latency assuming our network is good and up to date.

It's a lot easier to setup a simple and effective network compared to setting up distributed servers that run and store all our programs and data.

Another positive that is overlooked is that by making our servers and whatever services we need on the cloud, we are making our systems global in extremely little time. Instead of having to waste time connecting servers over the internet. The cloud does all the heavy lifting so users can connect from where ever and receive whatever they need. Plus, it's a lot easier to setup a simple and effective network compared to setting up distributed servers that run and store all our programs and data. So connecting to a cloud services makes things a lot more easy.

There are three main types of Cloud Computing Infrastructure as a Service (IaaS), Platform as a Service (PaaS), and Software as a Service (SaaS). IaaS is providing the essential infrastructure like storage, security, hosting, and processing, all while being the cheapest of the three.[^3] PaaS is a step above IaaS in that it includes all of IaaS except now we are also given development tools and a system to do it in.[^4] Lastly, SaaS includes the two before it with licensing and hosted centrally.[^5] Common uses of SaaS are office software and email software.

![SaaS](images/what-is-saas.png "SaaS")[^10]

## History of Cloud Computing

Often times we think of the cloud as synonymous with an incorporeal entity made up of thousands of remote data centers. We even believe it to be contingent on the internet. However, the theory's that led to its existence were explored prior to the internet's creation. The ability for computers to communicate with each other was first written in as a requisite by the Defense Advanced Research Projects Agency's funding of MIT's project MAC. MAC's purpose was to successfully establish a one-to-many relationship between multiple users and a single computer provided as an access point for software. This was done through a process known as hardware virtualization.

## Products

When it comes to cloud computing there are a lot of services that are shared among competitors. Services like processing, storage, hosting apps, databases management, and even AI. Yet no services are the same. Amazon Web Services has some cloud solutions that Microsoft Azure or Google Cloud doesn't have, and the same can go the other way. Since, all the services are trying to differentiate so they get more users and companies. So, it is important to know what services are needed for what we are trying to use the cloud so we can purchase the right services for the right problem. All three of the main competitors also give a lot of temporary free services to try and learn how to use them, while also giving always free services for everyone indefinitely.

The prevalence of cloud computing comes from its processing power, scalability, as well as its ability to use containers to create an OS agnostic development environment. Here we will look at some real world example of how cloud computing can aid in the creation of enterprise level software.

### Containers

Google Cloud gains an advantage over its competitors in OS virtualization due to its development of *_kubernetes_* container which is what all Amazon and Microsoft use for their cloud services today. Because of this working with Google Cloud will allow you immediate access to any new deployment or version of the kubernetes container. However, you will still be able to use it on the others just not on the latest patch.

### Processing
  
An upside to cloud computing is its ability to virtualize hardware that a given organization may require to undertake processing intensive tasks. We can think of hardware virtualization as a component in somebody elses being put onto the internet. Any given individual or enterprise can rent an instance of this hardware for an indefinite period of time. The majority of these cloud computing services offer the ability to create GPU instances which can be used to process sizable datasets. Due to the internet gaining worldwide adoption big data has become more and more prevalent. Because of this processing power has gained more and more prevalence within areas such as **Machine Learning** and **Finance**.[^10]

### Scalability

Along with processing powers cloud computing is unique in that the usage as hardware as an instance allow for immediate accessibility. For example if your application uses bottlenecks when performing a resource intensive tasks adding hardware is as quick as clicking a button. Compared to the one time expense of buying high-end hardware cloud computing proves not only to be quick but feasible. Imagine wanting to start a truck driving business delivering packages from pont A to B. The greatest initial cost you will encumber is the cost of the truck itself. It might be the case the alone is too expensive to payout at once so the owner chooses to rent the truck and pay with the profits generated. Cloud computing offers a similiar service rather than buying hardware outright you can instead rent the hardware needed for the given task. More importantly you can scale the hardware as the company makes more profit. To go back to our truck driving analogy this is like upgrading the trucks engine to do more deliveries as the business grows. Cloud Computing allows you to buy more features as you need them allowing businesses of all sizes to maximize profit through the building of scalable software.

### Amazon Web Services

---

Amazon is currently the biggest cloud service available in the market and still has a continuous growth.[^2] So, whether we are aiming to host something for peers or for work Amazon has what we need to build it. Even robotics, which is a solution only Amazon has. Amazon also comes with an impressive learning library with a lot of documentation on its services and products.[^6] While, we have not given a specific example for Amazon Web Services a lot can be found [here](https://aws.amazon.com/getting-started/).

### Google Cloud

---

Googles simplistic approach to pricing and services should not be confused with their complex infrastructure. So, whether you're a hobbyist programmer, contractor, or CTO of a multinational corporation one of the things you'll ask yourself is how good is the price to performance ratio of the service you are investing in. Google's cloud computing platform takes a minimalist approach to both its pricing as well as the services offered. Googles business model can be seen as using hefty discounts along with flexible software contracts in order to seize projects from their competitors in an attempt to corner shares in a market they had previously been late to. Another upside to Google cloud is the other products available from Google like Google maps or one of their other apps from an ever growing list, which can even be incorporated into our own apps and products.[^7]

#### Getting Started

For these examples we will be using Google Cloud for its user friendly infrastructure and installation. To get started simply go to google cloud and sign up for an account. Afterwards you'll be given a free trial with 300$ of credit. _note credit will expire after 12 months_. Thats it we're ready to start working on our examples.

##### Configuring multiple VM's

Here we will learn how to configure two vm instances. First, we'll create our instances to do this simply scroll down to vm instances on the left hand side of the dashboard and click on VM instances. After which you will see a popup click the create button on the popup.

Next we'll enter the instance name. For this example we will call this instance backend as it will be the backend for our app. **important**: _unless you will be building on top of the app being created click micro cpu under the dropdown below as this machine type will incur the least amount of debt.

Next we will select our boot disk, this is the virtualized instance our machine will boot off of. For this tutorial we will be picking Ubuntu 14.04 LTS

Afterwards we will check the Allow HTTP traffic this will allow us to make requests to and from our backend database.

From this point on you will incur incremental charges for as log as the instance remains active. These charges are negligible and will be covered as long as it doesn't exceed the credit we are given by google for creating our account.

Next we will create the frontend instance. This will use the same configuration as our backend instance.

Now we need to install MongoDB on our backend instance to store the data. Open the cloud console in the upper right hand corner of the screen.

Next we'll create our ssh key

```bash
gcloud compute --project "vmconfig" \
    ssh --zone <backend-zone> \
    <backend-name>
```

Once ssh finishes installing we will install our backend

```bash
sudo apt-get install update

sudo apt get install mongodb

```

Mongo DB will verify its installation simply enter y

The DB is now currently running. Before changing how it runs we mus first stop it

```bash
sudo service mongodb stop

```

Next we will run our mongodb database in the background on port 80

```bash

sudo mkdir $HOME/db --port \
80 --fork --logpath
 /var/tmp/mongodb
```

Now we are ready to exit the ssh session

```bash
 exit
```

 next we'll connect the frontend similar to the backend

```bash
 gcloud compute --project "vmconfig" \
    ssh --zone <frontend-zone> \
    <frontend-name>
```

install our dependencies

```bash
sudo apt-get update


curl -sL \
    https://deb.nodesource.com/setup_6.x \
    | sudo -E bash -

sudo apt-get install git nodejs
```

finally we will run our frontend app

```bash
  -clone the application
    git clone \
    https://github.com/GoogleCloudPlatform/todomvc-mongodb.git
```

-install any dependencies related to the repository

  ```bash
  cd todomvc-mongodb; npm install
  ```

-configure server

  ```bash
  sed -i -e 's/8080/80/g' server.js
  ```

-start the application

  ```bash
    sudo nohup nodejs server.js --be_ip \
    <backend-internal-ip> --fe_ip \
    <frontend-internal-ip> &
  ```

We're now finished and ready to exit our ssh session.

```bash
exit
```

Remember to delete each of the two instances when you are done using them to avoid incurring payments.

### Microsoft Azure

---

As stated before Microsoft Azure is similar to the other two in respect to services and usage. Yet Microsoft has a few differences compared to the other two. As a fourth type of Cloud Service Microsoft gives serverless computing while the competitors currently have the main three types of Cloud Computing. Plus, the documentation given by Microsoft not only has a simple and clean layout but is also easy to navigate around.[^8]

![Microsoft Azure](images/microsoft-azure-vector-logos-logo-zone-11212.png "Microsoft Azure logo")

#### Example

For the sake of the example we will be using Microsoft Azure. An upside to Microsoft Azure is its serverless option, which lets us execute and run code without creating a web virtual machine making testing and learning faster and easier. Though A little bit on creating a virtual machine will be covered at the end of the example. To start we want to make sure to have an IDE installed like Visual Studio Code, but any others could also work. It is also necessary to have the **Azure CLI**, which can be found [here](https://docs.microsoft.com/en-us/cli/azure/install-azure-cli?view=azure-cli-latest). Additionally, the language used for the code example is **Node.js** so, download it [here](https://nodejs.org/en/) if you need it also. Some current IDEs like Visual Studio Code even have extensions for Microsoft Azure to make things easier. It is still recommended to learn through the command line because the IDE we are using can be different in the future, yet the command line commands will still be the same. **.Net** framework is also needed but usually comes pre-installed on most computers.

The first step to be done is to setup Azure Function Core Tools.

- Windows
  
  We can simply use npm install in a command line to get the tools since **Node.js** is installed.

  `npm install -g azure-functions-core-tools`

- MacOS
  
  For MacOS we need to install **Homebrew** and **.NET** Core for macOS, which may or may not be already installed.
  
  ```bash
  brew tap azure/functions
  brew install azure-functions-core-tools
  ```

- Linux

  We need to install **.Net** Core for linux

  `sudo apt-get install azure-functions-core-tools`

we can also run a few commands to make sure things are installed and at a proper version.

```bash
npm -v
az --version
```

Now that we have installed Azure Core Tools, we can create a function, which is how the serverless environment is set up. But first we need to create a local function folder quite quickly and easily so we have a folder to work in. There are a lot of arguments that you can add to the command. For example, you can add `--source-control true`, which will create a git repository for the folder.

  `func init MyFunctionExample`

  It will immediately prompt you to pick a runtime and a language. This will also generate some files for us to use.

  ```bash
  PS C:\Users\Vector\Projects> func init MyFunctionExample
  Select a worker runtime: node
  Select a Language: javascript
  Writing .gitignore
  Writing host.json
  Writing local.settings.json
  Writing C:\Users\Vector\Projects\MyFunctionExample\.vscode\extensions.json
  ```

  However, we are still completely local at this point, so we need to create function in Azure. This will also prompt you to pick from a template to use, as well as name for the function. For this example, we will select **HTTP trigger**, which lets you run the function simply by calling a HTTP request. We will name the function `MyFirstFunction`.

  `func new`

  A helpful tip with Azure is to change the `authLevel` to "anonymous" in **function.json**, which was just created by the command, so you can work with the function without a function key that is always needed. Another file created by the function command is `index.js`. Index.js is code that will be ran by the function.

  We now have a working function that can be ran locally.

  `func host start`

  This will return quite a lot of lines, but the key lines to look for are that the **job host started**.

  ```node
  [4/17/2019 4:14:05 AM] Host initialized (188ms)
  [4/17/2019 4:14:05 AM] Host started (199ms)
  [4/17/2019 4:14:05 AM] Job host started
  Hosting environment: Production
  Content root path: C:\Users\Vector\Projects\MyFunctionExample
  Now listening on: http://0.0.0.0:7071
  Application started. Press Ctrl+C to shut down.

  Http Functions:

        MyFirstFunction: [GET,POST] http://localhost:7071/api/MyFirstFunction
  ```

  If we enter `http://localhost:7071/api/MyFirstFunction` into the browser, we get a response immediately.
  
  ```text
  Please pass a name on the query string or in the request body
  ```

  So, if we add `?name=<yourname>` we will get a different response.

  ```text
  Hello <yourname>
  ```

  And calling `control+C` we can end the local server running in our terminal.

  Now that we know that the function is working, we can now login to Azure to setup actually publish it to Microsoft Azure for it to be stored and ran on the cloud. To login we just need to call `az login`, which will bring you to a browser to login into Microsoft Azure. Afterwards we need to create a resource group to contain everything like our function. A few arguments are needed. `--name`, `--location`. To figure out locations there is command to run to list all the server locations with the argument `--sku FREE` to only search for free locations that we can use with our free trial.

  `az appservice list-locations --sku FREE`

  In this case we will pick `CentralUs` but it doesn't really matter, just make sure to stay consistent with your server choice.

  `az group create --name myFirstResourceGroup --location CentralUs`

  Afterwards we can create the storage needed by our function using the resource group we just made and its location. Again ,like last time we can use a `--sku` and `--kind` to pick out exact type of storage we want. We need to use `Standard_LRS` for `--sku`, since we are trying to make a function app, but we can skip `--kind`, since its default is fine Our name needs to be globally unique.

  `az storage account create --name storagegroup1 --location CentralUs --resource-group MyFirstResourceGroup --sku Standard_LRS`

  We can now create function application to host the function we made. Just like the storage creation we need a unique name. The new arguments needed for this command are `--consumption-plan-location`, which is just the location we picked, and `--runtime`, which is the language we chose.

  `az functionapp create --name myFirstExampleFunctions --resource-group myFirstResourceGroup --storage-account storagegroup1 --consumption-plan-location CentralUS --runtime node`

  Now that our function app has been made, we can publish it.

  `func azure functionapp publish myFirstExampleFunctions`

  ```text
  Getting site publishing info...
  Creating archive for current directory...
  Uploading 2.55 MB [###############################################################################]
  Upload completed successfully.
  Deployment completed successfully.
  Syncing triggers...
  Functions in myFirstExampleFunction:
    MyFirstFunction - [httpTrigger]
        Invoke url: https://myfirstexamplefunctions.azurewebsites.net/api/myfirstfunction
  ```

  The invoke Url given is the website name for the function application we made. We can test our function by putting in the name with the Url into a browser.

  `https://myfirstexamplefunctions.azurewebsites.net/api/myfirstfunction?name=<yourname>`

  Congratulations we have now successfully created and published our app onto the cloud. There are a lot more we can do like change its domain name. We can even make changes to do the code and push updates to the hosted version. Like if we created a new module `timeModule` to give us the time and date.
  So, our `timeModule` looks like this:
  
  ```javascript
  exports.myDateTime = () => {
    return Date();
  };
  ```

  Now we can import this into `index.js` and add it to the body of the `context.res`.

  ```javascript
  var time = require('./timeModule');
  ```

  ```javascript
  body: "Hello " + (req.query.name || req.body.name) + " \nThe current date and time is " + time.myDateTime()
  ```

  To update our app all we must to do is call `func azure functionapp publish myFirstExampleFunctions` again.

  If you want to delete this ResourceGroup, storage, and function you can call `az group delete --name MyFirstResourceGroup` and accept with `y`.
  
  We can also connect our repository to a version control like using git. First, we need to create a **Azure DevOps Account**, which is free and can be done [here](https://azure.microsoft.com/en-us/services/devops/), and do not forget to create a project. Next initialize a git using `git init .` and make an initial commit.

  ```bash
  git add *
  git commit 'first commit'
  ```

  After committing we need to first add the **Azure DevOps Extension** and create an Azure repository. For `--organization` and `--project` we need to add the organization and project name respectively from **DevOps** account we just made.

  `az extension add --name azure-devops`

  `az repos create --name <repositoryName> --organization https://dev.azure.com/<organizationName> --project <projectName>`
  
  Which will output a `remoteUrl`, which is needed to connect the git repository

  ```text
  "remoteUrl": "https://<Name>@dev.azure.com/<organizationName>/<projectName>/_git/<repositoryName>",
  ```

  Next, we just need to connect the remote using `git remote add origin`. Do not forget to push at the end.

  `git remote add origin https://<Name>@dev.azure.com/<organizationName>/<projectName>/_git/<repositoryName>`

  `git push origin master`

  This is optional but azure DevOps does give interesting deployment methods and options. Worth looking into, since it might be a useful skill.

## Other

---

  A recently new idea came about recently in cloud computing, one that is made for more personal and home use. The idea is using the cloud to play a game and stream it to a person's home. People would be able to enjoy their games wherever they want at the touch of a button and an internet connection. Another positive is that it will be a lot cheaper than buying a gaming computer, which is out of most people's price range. Companies like Google have been producing this technology for quite a while now. And with latest graphics cards being stronger than ever, one part of their problem is solved. There is however, one huge problem, bandwidth. Since, services like Google Stadia and others want to stream games at 4k Resolution, it takes a huge amount of bandwidth to keep a constant FPS and image quality. And while internet speeds have been going up, we have not reached a point where people have near gigabit speeds constantly. So even if a person can hit these speeds it is hard to keep them going constantly, especially in the day when other people are using the internet just as much as the person attempting to play games. This is still a very important part of cloud computing because it is pushing it further into what other things, we can accomplish with cloud computing.

  ![Google Stadia](images/Stadia_logo.svg "Google Stadia")

### Sources

[^1]: “What Is Cloud Computing?” *A Beginner's Guide | Microsoft Azure*, Microsoft, [azure.microsoft.com/en-us/overview/what-is-cloud-computing/](https://azure.microsoft.com/en-us/overview/what-is-cloud-computing/). Accessed 4 April 2019.

[^2]: Krazit, Tom. “State of the Cloud: Amazon Web Services Is Bigger than Its Other Four Major Competitors, Combined.” *GeekWire*, 3 Aug. 2018, [www.geekwire.com/2018/state-cloud-amazon-web-services-bigger-four-major-competitors-combined/](https://www.geekwire.com/2018/state-cloud-amazon-web-services-bigger-four-major-competitors-combined/). Accessed 7 April 2019.

[^3]: “What Is SaaS?” *Software as a Service | Microsoft Azure*, Microsoft, [azure.microsoft.com/en-us/overview/what-is-saas/](https://azure.microsoft.com/en-us/overview/what-is-saas/). Accessed 14 April 2019.

[^4]: “What Is PaaS?” *Platform as a Service | Microsoft Azure*, [azure.microsoft.com/en-us/overview/what-is-paas/](https://azure.microsoft.com/en-us/overview/what-is-paas/). Accessed 14 April 2019.

[^5]: “What Is IaaS?” *Infrastructure as a Service | Microsoft Azure*, [azure.microsoft.com/en-us/overview/what-is-iaas/](https://azure.microsoft.com/en-us/overview/what-is-iaas/). Accessed 14 April 2019.

[^6]: "AWS Documentation" *Amazon Web Services*, Amazon [docs.aws.amazon.com/index.html?nc2=h_ql_doc](https://docs.aws.amazon.com/index.html?nc2=h_ql_doc). Accessed 16 April 2019.

[^7]: "Google Cloud Platform Documentation" *Google Cloud*, Google, [cloud.google.com/docs/](https://cloud.google.com/docs/). Accessed 16 April 2019.

[^8]: “Microsoft Azure Documentation.” *Microsoft Docs*, Microsoft, [docs.microsoft.com/en-us/azure/](https://docs.microsoft.com/en-us/azure/). Accessed 16 April 2019.

[^9]: Thinkwik. “Cloud Computing digital image.” **Medium**, Medium, 19 Oct. 2018, [medium.com/@thinkwik/how-edge-and-fog-computing-are-taking-over-traditional-cloud-computing-b26b7276f1ce](https://medium.com/@thinkwik/how-edge-and-fog-computing-are-taking-over-traditional-cloud-computing-b26b7276f1ce).

[^10]: “What Is SaaS digital image” *Microsoft Azure*, Microsoft, [azure.microsoft.com/en-us/overview/what-is-saas/](https://azure.microsoft.com/en-us/overview/what-is-saas/).