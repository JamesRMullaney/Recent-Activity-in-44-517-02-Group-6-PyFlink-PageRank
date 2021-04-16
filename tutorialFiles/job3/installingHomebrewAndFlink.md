# Apache Flink | Homebrew Installation (Local Setup)
<line>

Throughout the course, we experience the Windows side of Big Data Analysis and Development. Through careful reasearch and analysis, here is a brief tutorial on how to setup Flink (Homebrew is requried) onto your Mac machine.

# Prerequisite
Prior to beginnnig the Flink installation, we must verify we have specific applications / services on our device.

1. Install Java if you have not already
    - Java is reuquired for this installation. If you are unsure if you have a valid Java version (1.8.0+ Version+), use the following command: ```  java -version ```.    
2. After Java has been verified, begin the installation for [Homebrew]("https://brew.sh"). You can find the detailed tutorial instructions [here]("https://brew.sh"). Below are some general instructions | tips:   
    
    <ol>

    <li> On your desktop, open Terminal. </li>

    <li> Within Terminal, enter the following commnad in its current directory. 
    <ul>
        <li>Note: When running the command, you may be prompted for your passsword. Just type in your appleID password, if that is what you are logged in last time.</li>
        <img src="./photo/Homebrew.png"> </img>
    </ul>

    <li> May Be Required: If you noticed that the installation prompts you to create a new <strong>PATH</strong>, run the two commands it prints out after the message. </li>

    <li> Once the installation has completed (returned to command line input), enter <code style="code { color: orange; padding: .5em;
    font-size: 105%; }>brew install wget</code>. This   will downlaod additioanl assets that weren't installed in the original installation. </li>
    
    </ol> 


