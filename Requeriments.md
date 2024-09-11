# Practical Work - Uncompressed Image Manipulation  


## Submission Mode
> The submission is group-based, with groups of 4 people.
If a member leaves the course, the remaining group members are still bound by the same conditions: the group is committed to completing the project. If any member leaves the course or does not contribute to the project submission, the remaining group members must fulfill the original commitment.
You must submit a file in the following format:
TP_Tópicos_2024_1c_viernes_{GROUP_NAME}.zip
For example: If the group is named “Invisible” and its members are Spinetta, Cerati, García, and Napolitano, the file should be named
TP_Tópicos_2024_1c_viernes_INVISIBLE.zip
Inside this file, there should be only two source files (without any containing folders) named funciones_estudiante.h and funciones_estudiante.c.
The file funciones_estudiante.c contains comments with fields to fill out with the members' information and a section for comments for the evaluator to read. The latter section is optional.
Groups must be formed and notified via MIEL messaging by 11:59 PM on Friday, May 3, 2024. The name of each group must be a single word and cannot be duplicated by another group.
The practical work has the value of a midterm exam and consists of a submission (group) and a defense (individual).

## Defense Mode
The defense is individual, in the lab. Modifications to the program will be requested to extend its functionalities.

## Submission Requirements
The project resolution must be submitted via the MIEL platform. The submission deadline is Sunday, May 18, at 11:59 PM.
Submissions that do not meet the specified deadline will not be valid.
The submitted practical work must function correctly, without warnings or compilation errors, and must fulfill all required functionalities.
It must adhere to the naming and file format specifications; otherwise, the submission will be invalid, and the project will be failed.
Groups should thoroughly review the practical work before submission, as resubmissions will not be accepted once submitted.
If the submission meets the conditions of date, correctly resolves each point indicated, has no warnings, and follows the proper file format, the project will be marked as “submitted.”
If the project is properly submitted but does not meet one of the requirements, a new submission and defense can be made. The new submission will have additional requirements that will be communicated accordingly. The defense will have the same conditions as the initial defense.

## Details to Consider
Images like the ones used in this project are composed of a header and a bit array representing the image. This bit array, given that each pixel has 24-bit depth, should be interpreted as a pixel with the content of 3 consecutive bytes.
It might be useful to use a hexadecimal dump program; if you don’t know any, you might even consider solving it as an extra point.
The three consecutive bytes are values between 0 and 255 (unsigned char), or more clearly in hexadecimal: 0x00 to 0xff, indicating the amount of color (red, green, or blue) in the image.
If the three RGB variables (Red, Green, Blue) are equal, the color will be gray, and depending on its intensity, it will approach white or black.
The color 0xffffff is white, while 0x000000 is black.
If we wanted to write a pure blue color, it should be 0x0000ff (with zero in the red component, zero in the green component, and 255 in the blue component).
Thus, 2^24 different colors can be created.
