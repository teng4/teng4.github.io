---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

<!-- {% if site.author.googlescholar %} -->
<!--   <div class="wordwrap">You can also find my articles on <a href="{{site.author.googlescholar}}">my Google Scholar profile</a>.</div> -->
<!-- {% endif %} -->

{% include base_path %}

You can also find my articles on my [Google Scholar](https://scholar.google.com/citations?user=lY0vLa0AAAAJ&hl=en) profile.


<!-- {% for post in site.publications reversed %} -->
<!--   {% include archive-single.html %} -->
<!-- {% endfor %} -->


------


Papers in journals
------
1. **Teng Li**, Amir Zakerimanesh, Yafei Ou, Armin Badre, and Mahdi Tavakoli. "Iterative Learning for Gravity Compensation in Impedance Control". IEEE/ASME Transactions on Mechatronics, pp. 1-12, **2024**. _(with a 3DOF PHANToM Premium 1.5A robot)_ [[IEEE Xplore](https://ieeexplore.ieee.org/document/10507161)] [[Demo Video](https://youtu.be/2BzboHYSa68)] [[ResearchGate](https://www.researchgate.net/publication/380049055_Iterative_Learning_for_Gravity_Compensation_in_Impedance_Control)]

      | _Demo video (click to watch the full video)_ |
      | [![This is a gif image.](../teng4_Papers/p008_TMECH_PDGit/TMECHfinalVideoExp3.gif)](https://youtu.be/2BzboHYSa68) |

      | _ABSTRACT: Robot-assisted arthroscopic surgery has been increasingly receiving attention in orthopedic surgery. To build a robot-assisted system, dynamic uncertainties can be a critical issue that could bring robot performance inaccuracy or even system instability if cannot be appropriately compensated. Disturbance observer is a common tool to be used for disturbance estimation and compensation by taking all uncertainties as disturbances, but this will refuse human-robot interaction since the human-applied force will also be regarded as a disturbance by the observer. Iterative learning for gravity compensation can be another promising way to solve this problem when gravity compensation is the main concern. In this paper, a gravity iterative learning (Git) scheme in Cartesian space for gravity compensation, integrating with an impedance controller, is presented. A steady-state scaling strategy is then proposed which released the updating requirements of the learning scheme and also extended its validity to trajectory-tracking scenarios from set-point regulations. The deriving process and convergence properties of the Git scheme are presented and theoretically analyzed, respectively. A series of simulations and physical experiments are conducted to evaluate the validity of the scaling strategy, the learning accuracy of the Git scheme, and the effectiveness of the learning-based impedance controller. Both simulation and experimental results demonstrate good performance and properties of the Git scheme and the learning-based impedance controller._ |

      
<!-- | _The proposed Git scheme is implemented in a simulated arthroscopic surgery scenario._ | -->
<!-- This is a image. --teng4note, use either method for image is ok, and use either absolut/relative path for image is also ok. -->
<!-- <img src="../teng4_Papers/p008_TMECH_PDGit/TMECHvideoImg1.jpg" width="50%" height="50%"> -->
<!-- This is a gif. -->
<!-- ![gift](../teng4_Papers/p008_TMECH_PDGit/TMECHvideoImg1.jpg) -->
<!-- Demo video (on Github): --teng4note, video not ok yet. -->
<!-- teng4_Papers/p008_TMECH_PDGit/TMECHfinalVideo.mp4 -->
<!-- Demo video (on Youtube): --teng4note, video not ok yet. -->
<!-- https://youtu.be/2BzboHYSa68 -->


------

2. **Teng Li**, Hongjun Xing, Ehsan Hashemi, Hamid D. Taghirad, Mahdi Tavakoli. "A Brief Survey of Observers for Disturbance Estimation and Compensation". Robotica, 41(12), 3818–3845, **2023**. Cambridge University Press. _(with a 3DOF PHANToM Premium 1.5A robot)_ [[Robotica OA](https://doi.org/10.1017/S0263574723001091)] [[Demo Video](https://youtu.be/6ePnym57jPU)] [[ResearchGate](https://www.researchgate.net/publication/374229090_A_Brief_Survey_of_Observers_for_Disturbance_Estimation_and_Compensation)]

      | _Demo video (click to watch the full video)_ |
      | [![This is a gif image.]()](https://youtu.be/6ePnym57jPU) |

      | _ABSTRACT: An accurate dynamic model of a robot is fundamentally important for a control system, while uncertainties residing in the model are inevitable in a physical robot system. The uncertainties can be categorized as internal disturbances and external disturbances in general. The former may include dynamic model errors and joint frictions, while the latter may include external payloads or human-exerted force to the robot. Disturbance observer is an important technique to estimate and compensate for the uncertainties of the dynamic model. Different types of disturbance observers have been developed to estimate the lumped uncertainties so far. In this paper, we conducted a brief survey on five typical types of observers from a perspective of practical implementation in a robot control system, including generalized momentum observer (GMO), joint velocity observer (JVOB), nonlinear disturbance observer (NDOB), disturbance Kalman filter (DKF), and extended state observer (ESO). First, we introduced the basics of each observer including equations and derivations. Two common types of disturbances are considered as two scenarios, that is, constant external disturbance and time-varying external disturbance. Then, the observers are separately implemented in each of the two simulated scenarios, and the disturbance tracking performance of each observer is presented while their performance in the same scenario has also been compared in the same figure. Finally, the main features and possible behaviors of each type of observer are summarized and discussed. This survey is devoted to helping readers learn the basic expressions of five typical observers and implement them in a robot control system._ |

------

3. **Teng Li**, Armin Badre, Farshid Alambeigi, and Mahdi Tavakoli. "Robotic Systems and Navigation Techniques in Orthopedics: A Historical Review". Applied Sciences, Section: Robotics and Automation, Special Issue: Surgical Robotics Design and Clinical Applications. 13(17):9768, **2023**. [[MDPI-applsci](https://www.mdpi.com/2076-3417/13/17/9768)] [[ResearchGate](https://www.researchgate.net/publication/373484618_Robotic_Systems_and_Navigation_Techniques_in_Orthopedics_A_Historical_Review)]

      | _ABSTRACT: Since the da Vinci surgical system was approved by the Food and Drug Administration (FDA) in 2000, the development and deployment of various robot-assisted minimally invasive surgery (MIS) systems have been largely expedited and boomed. With the rapid advancement of robotic techniques in recent decades, robot-assisted systems have been widely used in various surgeries including orthopedics. These robot-related techniques are transforming the conventional ways to conduct surgical procedures. Robot-assisted orthopedic surgeries have become more and more popular due to their potential benefits of increased accuracy and precision in surgical outcomes, enhanced reproducibility, reduced technical variability, decreased pain, and faster recovery time. In this paper, robotic systems and navigation techniques in typical orthopedic surgeries are reviewed, especially for arthroplasty. From the perspective of robotics and engineering, the systems and techniques are divided into two main categories, i.e., robotic systems (RSs), and computer-aided navigation systems (CANSs). The former is further divided into autonomous RS, hands-on RS, and teleoperated RS. For the latter, three key elements in CANS are introduced, including 3D modeling, registration, and navigation. Lastly, the potential advantages and disadvantages of the RS and CANS are summarized and discussed. Future perspectives on robotics in orthopedics, as well as the challenges, are presented._ |

------

4. **Teng Li**, Xiao Meng, and Mahdi Tavakoli. "Dual Mode pHRI-teleHRI Control System with A Hybrid Admittance-Force Controller for Ultrasound Imaging". Sensors, Section: Sensors and Robotics, Special Issue: Sensors Technology for Medical Robotics. 22(11):4025, **2022**.   _(with a 7DOF Franka Emika Panda robot)_ [[MDPI](https://www.mdpi.com/1424-8220/22/11/4025/htm)] [[Demo Video](https://youtu.be/NkqlawDmJrM)]  [[ResearchGate](https://www.researchgate.net/publication/360969094_Dual_Mode_pHRI-teleHRI_Control_System_with_a_Hybrid_Admittance-Force_Controller_for_Ultrasound_Imaging)]

      | _Demo video (click to watch the full video)_ |
      | [![This is a gif image.]()](https://youtu.be/NkqlawDmJrM) |

      | _ABSTRACT: The COVID-19 pandemic has brought unprecedented extreme pressure on the medical system due to the physical distance policy, especially for procedures such as ultrasound (US) imaging, which are usually carried out in person. Tele-operation systems are a promising way to avoid physical human-robot interaction (pHRI). However, the system usually requires another robot on the remote doctor side to provide haptic feedback, which makes it expensive and complex. To reduce the cost and system complexity, in this paper, we present a low-cost, easy-to-use, dual-mode pHRI-teleHRI control system with a custom-designed hybrid admittance-force controller for US imaging. The proposed system requires only a tracking camera rather than a sophisticated robot on the remote side. An audio feedback is designed for replacing haptic feedback on the remote side, and its sufficiency is experimentally verified. The experimental results indicate that the designed hybrid controller can significantly improve the task performance in both modes. Furthermore, the proposed system enables the user to conduct US imaging while complying with the physical distance policy, and allows them to seamlessly switch modes from one to another in an online manner. The novel system can be easily adapted to other medical applications beyond the pandemic, such as tele-healthcare, palpation, and auscultation. _ |

------


Papers in conferences
------
1. **Teng Li**, Armin Badre, Hamid D. Taghirad, and Mahdi Tavakoli. "Point-Based 3D Virtual Fixture Generating for Image-Guided and Robot-Assisted Surgery in Orthopedics". 2023 IEEE/ASME International Conference on Advanced Intelligent Mechatronics _(AIM 2023)_, June 28-30, Seattle, Washington, USA, **2023**. pp. 179-186. DOI: 10.1109/AIM46323.2023.10196130. _(with a 7DOF Franka Emika Panda robot)_ [[IEEE Xplore](https://ieeexplore.ieee.org/document/10196130)] [[Demo Video](https://youtu.be/ROSREHC9zU0)]  [[ResearchGate](https://www.researchgate.net/publication/371782677_Point-Based_3D_Virtual_Fixture_Generating_for_Image-Guided_and_Robot-Assisted_Surgery_in_Orthopedics)]

2. **Teng Li**, Armin Badre, Hamid D. Taghirad, and Mahdi Tavakoli. "Neural Network Learning of Robot Dynamic Uncertainties and Observer-Based External Disturbance Estimation for Impedance Control". 2023 IEEE/ASME International Conference on Advanced Intelligent Mechatronics _(AIM 2023)_, June 28-30, Seattle, Washington, USA, **2023**. pp. 591-597. DOI: 10.1109/AIM46323.2023.10196132. _(with a 3DOF PHANToM Premium 1.5A robot)_ [[IEEE Xplore](https://ieeexplore.ieee.org/document/10196132)]  [[ResearchGate](https://www.researchgate.net/publication/371782730_Neural_Network_Learning_of_Robot_Dynamic_Uncertainties_and_Observer-Based_External_Disturbance_Estimation_for_Impedance_Control)]

3. **Teng Li**, Armin Badre, Hamid D. Taghirad, and Mahdi Tavakoli. "Integrating Impedance Control and Nonlinear Disturbance Observer for Robot-Assisted Arthroscope Control in Elbow Arthroscopic Surgery". In 2022 IEEE/RSJ International Conference on Intelligent Robots and Systems _(IROS 2022)_, October 23-27, Kyoto, Japan, **2022**, pp. 11172-11179. doi: 10.1109/IROS47612.2022.9981208. _(with a 3DOF PHANToM Premium 1.5A robot)_ [[IEEE Xplore](https://ieeexplore.ieee.org/document/9981208)] [[Demo Video](https://youtu.be/f54Iah0yuWk)]  [[ResearchGate](https://www.researchgate.net/publication/364676968_Integrating_Impedance_Control_and_Nonlinear_Disturbance_Observer_for_Robot-Assisted_Arthroscope_Control_in_Elbow_Arthroscopic_Surgery)]

4. **Teng Li**, Hongjun Xing, Hamid D. Taghirad, and Mahdi Tavakoli. "EMG-Based Hybrid Impedance-Force Control for Human-Robot Collaboration on Ultrasound Imaging". In 2022 IEEE/RSJ International Conference on Intelligent Robots and Systems _(IROS 2022)_, October 23-27, Kyoto, Japan, **2022**, pp. 670-675. doi: 10.1109/IROS47612.2022.9981615. _(with a 7DOF Franka Emika Panda robot)_ [[IEEE Xplore](https://ieeexplore.ieee.org/document/9981615)] [[Demo Video](https://youtu.be/kgMYiFkA3qk)]  [[ResearchGate](https://www.researchgate.net/publication/364676896_EMG-based_Hybrid_Impedance-Force_Control_for_Human-Robot_Collaboration_on_Ultrasound_Imaging)]

5. **Teng Li**, Ali Torabi, Hongjun Xing, and Mahdi Tavakoli. "Improving A User’s Haptic Perceptual Sensitivity by Optimizing Effective Manipulability of A Redundant User Interface". In 2021 IEEE International Conference on Autonomous Systems _(ICAS 2021)_, August 11-13, Montreal, QC, Canada, **2021**, pp. 1–5. _(with a 4DOF planar robot)_ [[IEEE Xplore](https://ieeexplore.ieee.org/abstract/document/9551140)]  [[ResearchGate](https://www.researchgate.net/publication/353957917_IMPROVING_A_USER'S_HAPTIC_PERCEPTUAL_SENSITIVITY_BY_OPTIMIZING_EFFECTIVE_MANIPULABILITY_OF_A_REDUNDANT_USER_INTERFACE)]



