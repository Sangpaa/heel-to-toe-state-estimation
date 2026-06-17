# Heel-to-Toe State Estimation for Exoskeletons — Contact-Relative Invariant EKF

A contact-synthesized relative-SLAM correction for the contact-aided InEKF on a wide-footed
exoskeleton. As the broad foot rolls heel-to-toe the point-contact assumption fails and the
filter diverges (~14 m over an 80 s walk); measuring body motion *relative* to the stance foot
— purely from encoders + IMU, no camera — cuts drift to ~6.6 m (2.2x).

**Live page:** https://sangpaa.github.io/contact-relative-inekf/

Static single-page site (`index.html` + `static/`). No build step.
