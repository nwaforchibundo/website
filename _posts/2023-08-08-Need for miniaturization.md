---
layout: page
title: The Need for Miniaturization
subtitle: Benefits and importance of device miniaturization in biomedical application
cover-img: [/assets/img/path.jpg : Sojochukwu]
thumbnail-img: /assets/img/miniaturization1.gif
share-img: /assets/img/miniaturization1.gif
tags: [books, test]
---

{: .box-success} 
To further enhance MIS capabilities, there is a growing demand for smaller and more precise devices. 

Considering the most popular commercial surgical robotic system, which is da Vinci.  
It has more than 10 million MIS performed worldwide {% cite Badani2007 %},{% cite Ettorre9531355 %},{% cite marcus2014 %},{% cite intuitive2023 %}. This surgical robot uses instruments that are rigid and straight with articulating tips. 
In addition, they also have a large footprint in the operating room. Hence, the trend toward miniaturization of MIS tools is evident in order to maximize the benefits and advantages that come with it {% cite yang2018grand %}. 
Some of the key benefits or reasons for MIS device miniaturization include:
{: .text-justify}
1.  **Enable less invasive procedures:** With smaller devices, surgeons can perform interventions through smaller incisions or natural orifices, minimizing tissue damage and reducing patient trauma. 
    This approach results in faster healing times, shorter hospital stays, and improved patient outcomes.    
2. **Need for improved dexterity:** The availability of highly specialized instruments and devices allows surgeons to perform tasks swiftly with a high level of dexterity and reliability. 
    Indeed, miniaturized devices can navigate intricate anatomical structures, enabling surgeons to access challenging areas that were previously difficult to reach. 
    For example, transcatheter procedures like aortic valve replacement can now be performed entirely from a groin-area access site {% cite Onan20 %},{% cite Kalogeropoulos2022971762 %},{% cite TOGGWEILER2013643 %}, thanks to miniaturized devices.    
3. **Easy patient-specific adaptability:** In all cases, due to the fact that at the same scale, one has to adapt to the anatomy, this benefits by having a smaller device that can easily be customized to adapt patient-specific need or anatomy structure. 
    There is a higher benefit/possibility of organ collision avoidance using a miniaturized MIS device.   
4. **Cost reduction and improvement of patient comfort:** Smaller devices require fewer resources and materials, resulting in cost savings in manufacturing and medical procedures. 
    Additionally, the use of miniaturized devices can contribute to reduced pain, scarring, and discomfort for patients, enhancing their overall experience during and after surgery.
 {: .text-justify}   

As technology advances, the convergence of various aspects is expected to drive development in terms of smaller, more dexterous, and less expensive devices for a wide range of procedures. 
The ongoing improvements in MIS device miniaturization are vital for pushing the boundaries of what is possible in surgical interventions, ultimately leading to enhanced patient care and outcomes.
Therefore, having manipulators that are scalable to a small size, flexible yet strong, and capable of reaching difficult-to-access surgical sites via complex pathways and completing the surgical task with dexterity would be extremely beneficial. 
Continuum robots with small sizes are more suitable for MIS compared to using straight rigid instruments {% cite Burgner7314984 %}. 
Although, among all the different types of medical robots, the continuum robot has witnessed a sporadic rise in research and the highest publication throughput currently. 
Yet, one major aspect of research and need in the field of medicine that was identified was the area of miniaturization {% cite yang2018grand %}. 
In as much the importance of robots in medicine is undoubtedly overemphasized, there are still large areas calling for a research breakthrough, especially in microsurgery and micromanipulation.
{: .text-justify}

Miniaturized manipulators are designed to manipulate small objects with a high degree of accuracy and repeatability in confined spaces. 
These devices have a wide range of applications in different fields, such as the manipulation of samples inside scanning electron microscopes (SEM) or for endoscopic medical procedures. 
For endoscopic medical procedures, the manipulators are inserted into the body through small incisions and are used to perform delicate procedures, such as imaging, biopsy, suturing, or removing small tissue samples. 
Inside SEM, miniaturized manipulators are used for handling samples for imaging, performing various measurements, or assembling components. 
One of the current challenges of micromanipulation e.g in SEM or medical is to increase the dexterity of the manipulators by integrating rotations at the distal end, to actualize tool orientation with large angles. 
Indeed, the three translational movements of the end-effector in the *x, y*, and *z* axis, can be generated by proximal joints, whereas only distal ones can  produce the orientation of the tool. 
Having a distal orientation section is well known to improve manipulator dexterity {% cite Wu7801024 %},{% cite CHIKHAOUI2016234 %},{% cite Peyron2022MagneticCT %},{% cite LI2017148 %}.
{: .text-justify}

When considering parallel manipulators, which has many advantages such as high precision, high speed, high payload/force capabilities, and extrinsic actuation, 
that enable locating the actuators outside of the confined space leading to a very high miniaturization potential but they are often limited in workspace volume {% cite Jin2015 %}. 
Presently, the smallest parallel manipulators in the literature include Millidelta {% cite mcclintock2018millidelta %} and Migribot {% cite abn4292 %}. 
Though each presents key benefits thanks to their parallel configurations, they are both restricted to translative motion. 
Conversely, this issue and limitation can be solved using a new type of parallel robot called parallel continuum robots (PCRs) {% cite bryson_toward_2014 %}. 
For this reason, added to the benefits and possibilities of using flexible glass at a small scale, this is one of the key research investigations and analyses in this dissertation.
{: .text-justify}

![Ladder1]({{ '/assets/img/two/Ladder1.png' | relative_url }})
**Figure 1.** *<span style='color: orangered;'>Trend in medical robotic devices with a paradigm shift from rigid link/articulated robots to continuum robots on the bases of backbone flexibility and level of miniaturization.</span>*
{: .text-justify}

Current MIS tools still have challenges to access some confined regions of surgical sites due to the size, location, or sensitivity/complexity nature of anatomical structure e.g. when considering the use of the conventional rigid straight instrument. 
Considering the trend in medicine for further miniaturization, which targets the possibility of accessing hard-to-reach zone of interest. 
In fact, the rising trend in medicine for micro-port multi-deployment strategy has given rise to the need for the development of devices that can meet the demand, especially in neurosurgery. 
The ongoing advancements in MIS device miniaturization contribute to the evolution of surgical techniques, offering numerous benefits to patients and healthcare providers alike. 
In general, the need for miniaturization has motivated the rise in small-scale smart devices, which are proposed for microsurgery or MIS, and has paved the way for the high research throughput in compact continuum robots. 
The trend for further miniaturization with its benefits, has put continuum robots on top of the ladder among clinical instruments and devices for MIS (refer to Fig. 1).
{: .text-justify}

In Fig. 1, concentric tube robots (CTRs) are at the top of the ladder when considering the level of backbone flexibility due to no redundant joint by disk. 
In the case of miniaturization, they are simply composed of nested pre-curved tubes that can be easily scaled down sub-millimeter level. 
Considering the conventional use of Nitinol for continuum robot fabrication, which is now the predominant material for prototyping different continuum robots in the literature. 
However, researchers had reached a stagnating point of constant use of Nitinol and then began to call for investigation of other viable materials {% cite gilbert2016concentric %}. 
These paved the way for the use of 3D print materials but unfortunately, the process is highly dependent on the printer setting, and output or mechanical qualities were poor compared to the use of Nitinol. 
To that effect and in regard to the present demand for further miniaturization, we considered and explored the use of glass at a small scale for the fabrication of miniaturized continuum robots. 
Since thin glass at a small scale is flexible e.g. optical fiber, this presents great benefits considering the inherent properties of glass like the light carry capacity, 
and this will open entirely new doors in the domain of continuum robots along with the application potentials.
{: .text-justify}

<!---
### Notification

{: .box-note}
**Note:** This is a notification box.

### Warning

{: .box-warning}
**Warning:** This is a warning box.

### Error

{: .box-error}
**Error:** This is an error box.
--->

References
----------

{% bibliography --cited %}

<h1>
      <span id="txt-rotate" data-period="500" data-rotate='["In all you do", "Please remain focused."]'>

      
