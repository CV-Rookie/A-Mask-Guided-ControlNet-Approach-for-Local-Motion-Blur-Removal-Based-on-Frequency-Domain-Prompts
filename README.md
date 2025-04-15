# A-Mask-Guided-ControlNet-Approach-for-Local-Motion-Blur-Removal-Based-on-Frequency-Domain-Prompts
In real-world photography, objects undergo motion during exposure, result-
ing in the blending of dynamic objects with static backgrounds. Traditional
image deblurring methods primarily focus on global restoration, often com-
promising the sharpness of non-blurred regions and introducing unnecessary
computational overhead. Current local motion blur algorithms exhibit in-
sufficient accuracy in segmenting blurred regions. To address these limita-
tions, this paper presents a novel local motion deblurring framework that
utilizes a frequency-aware, prompt-based mask generation model to guide
the deblurring process. The model fine-tunes the Segment Anything model
(SAM) using frequency-domain information to generate accurate motion blur
masks, which are then used as conditional inputs to the control network for
targeted deblurring. By explicitly locating the blurred regions, this approach
prevents unnecessary modifications to the sharp areas, while improving com-
putational efficiency. Extensive experiments demonstrate that the proposed
method outperforms state-of-the-art deblurring techniques in terms of per-
ceptual quality and quantitative metrics. The proposed framework achieves
effective local motion deblurring while preserving the integrity of non-blurred
regions. 
