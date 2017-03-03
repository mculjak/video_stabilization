# Video stabilization for unmanned aerial vehicles

Video surveillance of traffic intersections acquired by unmanned aerial vehicles (UAV) gives us valuable traffic flow information. However, such videos are not suitable for direct analysis by using background modeling due to vehicle motion, so we first need to stabilize given video. This work explores one approach to video stabilization system for unmanned aerial vehicles. The process of stabilization is based on Kanade-Lucas-Tomasi feature tracker and estimation of homography with respect to reference video image. This work describes used method of tracking, homography estimation and image warping, and also recovering lost features which enables long-term video stabilization. The system is evaluated on traffic intersection videos, and review of results is given. Long-term video stabilization with respect to reference video image is achieved, with little deviation from reference image plane. Stabilization is successful when camera tries to film location of reference image.

Master thesis (in Croatian): https://github.com/mculjak/video_stabilization/blob/master/culjak12dipl.pdf

- Original videos: https://github.com/mculjak/video_stabilization/blob/master/prvi-nestabilno.avi
- Stabilized videos: 
 https://github.com/mculjak/video_stabilization/blob/master/prvi-stabilno.avi ,
 https://github.com/mculjak/video_stabilization/blob/master/jankomir-stabilno.avi
