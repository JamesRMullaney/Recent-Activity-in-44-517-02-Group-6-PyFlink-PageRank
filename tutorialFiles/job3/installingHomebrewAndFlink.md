# Apache Flink | Homebrew Installation (Local Setup)
<line>

Throughout the course, we experience the Windows side of Big Data Analysis and Development. Through careful reasearch and analysis, here is a brief tutorial on how to setup Flink (Homebrew is requried) onto your Mac machine.

# Prerequisite
Prior to beginnnig the Flink installation, we must verify we have specific applications / services on our device.

1. Install Java if you have not already
    - Java is reuquired for this installation. If you are unsure if you have a valid Java version (1.8.0+ Version+), use the following command: ```  java -version ```.    
2. After Java has been verified, begin the installation for [Homebrew]("https://brew.sh"). You can find the detailed tutorial instructions [here]("https://brew.sh"). Below are some general instructions | tips:   
    
3. On your desktop, open Terminal. </li>

4.  Within Terminal, enter the following commnad in its current directory. 
    
    <code> $ brew install apache-flink </code>
        
5. (?) <strong>May Be Required:</strong> If you noticed that the installation prompts you to create a new <strong>PATH</strong>, run the two commands it prints out after the message. </li>
    <p> Once the installation has completed (a.k.a. returned to command line input), enter:<div style="color: orange; padding: .5em; font-size: 105%;"}>brew install wget</div> This will downloadv b vv bbbvb additioanl assets that weren't installed in the original installation. </p>    </ol> 

## Download and Install Apache-Flink
With Java and Homebrew installed locally on your Mac device, we can now procede to download and install Flink. To begin, use Homebrew to install Apache Flink.

```Terminal
$ brew install apache-flink
...
$ flink --version
Version: _._._, Commit Id: ______
```

![](../photo/Images/installFlink.png)

## Start a Local Flink Cluster
Once we get Flink installed onto our device, we can then begin and run our first Flink Cluster. To begin, 

```Terminal
cd ../../opt/homebrew/Cellar/apache-flink/1.12.2/libexec/bin   # Navigate to the bin folder
sh start-cluster.sh # Call and open cluster file 
```
![](../photo/Images/start-cluster.png)

Once the cluster has been created, we should be able to go to http://localhost:8081 and see the Flink dashboard with oen available asset. 

![](../photo/Images/hostPage.png)


# Optional: Read and Understand the Code: SocketWindowWordCount (Java)
As developers, we work in an enviroment where change is constant. For instance, ten years ago, we were using programming languages that could be discontinued or improved to other versions. However, all conding works together, so the intial 'on-boarding' by an employee will take less and less time.

For those who are curious, here is a short part of the SocketWindowWordCount fumction for you to analyze and make comments on!

<!-- Note: All code below was found directly from  -->
```Java



```
