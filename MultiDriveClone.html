#Business Need

The IT department requires a method to clone a single USB drive to multiple USB drives simultaneously. This process must replicate the entire drive, not just an ISO image. Critical components such as the autounattend configuration and package files must reside outside the OS image in order to be detected and executed correctly during deployment.

Commercial USB replication devices are available and meet this requirement; however, they typically cost approximately $500 per unit. The objective of this project is to identify a software-based solution that achieves comparable functionality at a significantly lower cost.

Tool Evaluation: Balena Etcher
Test 1 – Single-Drive Cloning

##Objective
Evaluate whether Balena Etcher can perform a true, full-disk clone (as opposed to writing an ISO image) and establish baseline terminology and behavior around “cloning” versus “imaging.”

##Method
A USB drive that had previously been wiped due to an incorrect drive reference during the wipedisk argument in the Windows auto-unattend process was used as the source. This ensured the test validated a full-disk clone, including all required non-ISO components.

##Result
The cloning process completed successfully. The destination drive was an exact replica of the source drive, including all required files and configurations. This confirms that Balena Etcher performs a true disk-level clone.

##Conclusion
While Balena Etcher achieves the desired technical outcome, it only supports cloning to a single destination drive at a time. Running multiple instances in parallel would be manual and significantly slower, making it impractical for scaled deployment. This test successfully validated the concept but does not meet the scalability requirement.

#Tool Evaluation: ImageUSB
Test 1 – Single-Drive Imaging and Restoration

##Objective
Confirm that ImageUSB can produce the same results as Balena Etcher for a single USB drive, with the long-term goal of scaling to multiple simultaneous writes.

##Method
Unlike Balena Etcher, ImageUSB requires the creation of an image file prior to deployment. A full-disk image (.bin) was created from the source USB drive. That image was then written to a blank USB drive using ImageUSB.

##Result
During the write process, ImageUSB returned the following error:

Failed to write to \.\PhysicalDrive1 at offset 15523119104 (0x9d400000)

Despite this error, inspection of the destination drive indicated that all files and partitions appeared intact.

Validation Test – OS Installation
To verify functional integrity, the cloned USB drive was used to install Windows 11 on a laptop. The installation proceeded as expected and completed successfully, including all imaging and configuration steps.

##Conclusion
Although ImageUSB reported a write error, the cloned drive functioned correctly in a real-world deployment scenario. Based on successful OS installation and configuration, this test is considered a pass. The imaging process was repeated to validate consistency with newly generated images.

###Test 2 – Multi-Drive Imaging

##Objective
Determine whether ImageUSB can image multiple USB drives simultaneously, or at minimum initiate multiple writes concurrently.

##Method
Three blank USB drives were connected to the system and provided with a previously validated (“old”) .bin image file for deployment.

(Testing in progress / results to be documented.)

#Summary

This evaluation demonstrates that software-based USB cloning is technically viable without dedicated replication hardware. Balena Etcher confirms the feasibility of full-disk cloning, while ImageUSB shows promise as a scalable solution capable of multi-drive imaging. Further testing will focus on simultaneous deployment performance and USB hub compatibility to assess suitability for mass production scenarios.
