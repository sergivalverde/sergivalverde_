
# Cases where it doesn't work
SAJ27: Lesion classified as class 6 in the basal, so the algorithm thinks that it's WM already. 

![](../Pasted%20image%2020221224104008.png)

SAJ20: error in tissue segmentation

![](../Screenshot%202022-12-25%20at%2010.59.12.png)

# Segmentation
I can use the 0.05 threshold to report a better lesion segmentation :) 

# Configuration

## configuration with NL means (nl default)
> (0.15, 5, 1, 1, 0.1),
> (0.15, 10, 0.85, 0.85, 0.1),
> (0.2, 15, 0.7, 0.75, 0.1),
> (0.3, 15, 0.5, 0.5, 0.05), #0.05
> (0.4, 10, 0.5, 0.5, 0.025)]): # 0.025

# new ideas
- what it happens if I reduce the size on > 0.3 (with nl r=1)
- Process synthesis errors
- ![](../media/Pasted%20image%2020230211082343.png)