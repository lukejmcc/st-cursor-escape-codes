# st-cursor-escape-codes


Allows you to change the cursor color.

110-117 for colors 0-7

echo -e "\033[111m" for red

120-127 for bright colors 8-15

echo -e "\033[121m" for bright red

make sure defaultrcs is set to 256 in config.h

echo -e "\033[130m" to reset

