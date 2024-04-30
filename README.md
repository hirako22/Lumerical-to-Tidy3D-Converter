This is some experimental code that takes in a .lsf file representing a Lumerical project and converts it to an equivalent Tidy3D python file. Note that not every object in Lumerical can be converted/has a Tidy3D counterpart, and vise versa. There are also default values that are assumed in Lumerical but needed in Tidy3D for some objects, and vise versa. The final python output should be checked and used as a starting point in order to ensure accurate transfer.

To convert, run the function converter_arg("your_lumerical_file_name.lsf", "your_desired_output_name.py")
