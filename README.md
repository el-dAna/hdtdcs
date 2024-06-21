# HIGH-DEFINITION TRANSCRANIAL DIRECT CURRENT STIMULATION (hdtdcs) DEVICE DESIGN AND IMPLEMENTATION. (TÜBİTAK)
Circiut design showing major componets and functionality.
<img width="629" alt="image" src="https://github.com/el-dAna/hdtdcs/assets/100404513/1c6b481b-cdff-43a4-86cc-d5f011dc6241">

High Difinition Transcranial Direct Current Stimulation basically is the idea of passing direct current (usually 2mA) through electrodes through the skull to enhance(polarise) or suppress(hyperpolarise) brain activity.
This project was aimed at designing and constructing a functional hd-TDCS device for the potential treatment of derug resistant epilepsy.
## What is TDCS


## What is hd-TDCS

## Advantages of hd-TDCS

## Circuit description and function

#### Falstad simulation
The insert below is a screen shot of the main function of the circuit on falstad. It shows the major components: 9V DC voltage source, 12bit DAC and transistors. We implemeented a 6 electrode hdTDCS (1 anode+ and 5 cathodes-) for the potential application in the treatment of drug resistant focal epilepsy. The point at which the 6 wires meet is the practical position of the head. As shown, current through the cathodes is 2mA and total current through anode is 10mA approx. 
<div><img width="500" height='300' alt="image" src="https://github.com/el-dAna/hdtdcs/assets/100404513/13396a92-639d-459b-9cb6-50d0206788a3"></div>

#### Lab implementation
The image below is the soldered version in the lab. We verified the output volage from the DAC to the bases of the transistors. Practically the input DC voltage should be kept at 9V so we included a 9V regulator and supplied >9V.
<div><img width="200" height='200' alt="image" src="https://github.com/el-dAna/hdtdcs/blob/main/images/20230921_132242.jpg"></div>


#### Final prototype case
The case is to contain the circuit board, microcontroller and voltage source. Side ports included for easy plugging of microcontroller to computer for easy debugging. 
<div><img width="200" height='200' alt="image" src="https://github.com/el-dAna/hdtdcs/blob/main/images/20230921_131836.jpg"></div>

## AutoCad Designs
#### The electrode and gel holder from conception to CAD design to 3D printing.
<img width="609" alt="image" src="https://github.com/el-dAna/hdtdcs/assets/100404513/28434324-e294-4d12-838c-fd571a066e4e">

#### The head strio and electrode holder CAD designs.
<img width="609" alt="image" src="https://github.com/el-dAna/hdtdcs/assets/100404513/4024b09a-8322-4942-9dea-f599288a7982">



## [Simibs](https://simnibs.github.io/simnibs/build/html/index.html) Current Distribution Simulation MRI scans.
#### Simnibs is an open surce software for non-invasive brain stimulation(TMS-Transcranila Magnetic Stimulation and TDCS-Transcranial Direct Current Stimulation) simulation.
<img width="657" alt="image" src="https://github.com/el-dAna/hdtdcs/assets/100404513/dc169371-f0ac-4a6d-b721-7feee4cc358e">


## Contributors
Marya Alhajmohammadothman
Benjamin Sogodam Atadana [X](https://twitter.com/hey_eldana)

## Supervisors
Prof. Dr. Hilal Göktaş [X](https://twitter.com/Goktashil)
Prof. Dr. Mehmet Yüksekkaya

## Funding
2209-A Üniversite Öğrencileri Araştırma
Projeleri Destekleme Programı 2022 Yılı 2.
[X](https://twitter.com/Tubitak)




