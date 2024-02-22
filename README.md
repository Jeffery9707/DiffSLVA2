# Diffusion Models for Sign Language Video Anonymization

## This repository contains demos for Diffusion Models for Sign Language Video Anonymization
We propose text-guided sign language video anonymization. 
We improved the facial expression enhancement module by fine-tuning the image animation models on our mixed dataset with balanced sampling.

## Anonymization result examples:

![Screenshot](demos/6188928_hed0_100_compare.gif)

(1) Input prompt for anonymization: a superman in blue uniform is making gestures

![Screenshot](demos/6188928_hed0_101_compare.gif)

(2) Input prompt for anonymization: a handsome man in CG style, blonde hair, is making gestures

![Screenshot](demos/6188928_nhed1_wm_compare.gif)

(3) Input prompt for anonymization: a beautiful woman in CG style, brown hair, is making gestures

The originial sign videos in (1)-(3) are taken from ASLLRP file Cory_2013-6-27_sc115, Utterance 22, meaning 'If friends play Frisbee, I will join them.’ 

Includes non-manual marking of conditional in the first clause.

![Screenshot](demos/633534_nhed1_compare_keep.gif)

(4) Input prompt for anonymization: a handsome man in CG style, blonde hair, is making gestures

![Screenshot](demos/633534_nhed2_compare_keep.gif)

(5) Input prompt for anonymization: a Chinese man in Chinese ink wash painting is making gestures

The originial sign videos in (4)-(5) are taken from ASLLRP file Cory_2013-6-27_sc113, Utterance 28, meaning ‘Where do you work?’

Includes non-manual marking for wh-questions over the final sign in the sentence (WHERE).

![Screenshot](demos/8397739_nhed1_compare_keep.gif)

(6) Input prompt for anonymization: a handsome man in CG style, blonde hair, is making gestures

The originial sign video in (6) is taken from ASLLRP file Cory_2013-6-27_sc109, Utterance 33, meaning ‘I like it, if it has butter, I'm fine with that.’

Includes non-manual marking of conditional over the middle clause.

![Screenshot](demos/79801108_nhed1_wm_compare.gif)

(7) Input prompt for anonymization: a beautiful woman in CG style, brown hair, is making gestures

The originial sign video in (7) is taken from ASLLRP file Cory_2013-6-27_sc114, Utterance 10, meaning 'I commute to work by bike because I can't afford a car.'

Includes non-manual rhetorical question marking over the sign WHY.


![Screenshot](demos/6186858_nhed1_compare_keep.gif)

(8) Input prompt for anonymization: a handsome man in CG style, blonde hair, is making gestures

The originial sign video in (8) is taken from ASLLRP file Cory_2013-6-27_sc115, Utterance 53, meaning 'I hate commuting to work by bike.'

Includes a negative head shake at the end of the sentence.


## Facial Expression Preservation Comparison:

In this section, we present a comparison illustrating the impact of our fine-tuned facial expression enhancement module. The comparison is structured across three rows for clarity. The first row showcases video frames from the original sign language video, including the face of the original signer for reference. The second row displays the anonymized video produced without the integration of our facial expression enhancement module, offering a baseline for comparison. The final row reveals the anonymized video after the application of our facial expression enhancement module, highlighting the module's effectiveness. The comparative analysis clearly demonstrates that our module significantly enhances the generation of facial expressions, leading to more expressive and natural-looking videos.

![Screenshot](demos/7118_head_2.gif)

(9) Input prompt for anonymization: a superman in blue uniform is making gestures

The originial sign video in (9) is taken from ASLLRP file Cory_2013-6-27_sc115, Utterance 22, meaning 'If friends play Frisbee, I will join them.’ 

Includes non-manual marking of conditional in the first clause.

![Screenshot](demos/79801108_head_2.gif)

(10) Input prompt for anonymization: a beautiful woman in CG style, brown hair, is making gestures

The originial sign video in (10) is taken from ASLLRP file Cory_2013-6-27_sc114, Utterance 10, meaning 'I commute to work by bike because I can't afford a car.'

Includes non-manual rhetorical question marking over the sign WHY.

