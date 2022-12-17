install python > 3.8
install pandas
install numpy
install matplotlib
install NetLogo 6.2.2

open the python file in vscode 
right click and then 
select the option of run python in terminal.

Here are parameters which need to be set up according to our desired experiment.

oldVersion = "false"       # keeping this parameter true to run the old version and the rest to false
Enable_Education = "true"    # set this parameter as true if we want to evaluate the effect of education
enable_inheritance_tax = "true"   # set this parameter as true if we want to evaluate the effect of inheritance tax
enable_flat_inh = "true"       # set this parameter as true if we want to evaluate the effect of flat tax if the inheritance tax is true
   
num_people = 700               #at least 2 and at most 1000

max_vision = 15                  # set it between 1 to 15
metabolism_max = 25             # set it between 1 to 25

life_expectancy_min = 55         # set it between 1 to 100
life_expectancy_max =  77       # set it between 1 to 100

percent_best_land = 25          # set it between 5 to 25 
grain_growth_interval = 1       # set it between 1 to 10
num_grain_grown = 10            # set it between 1 to 10

poor_vision_max = 2             # set it between 0 to max-vision
mid_vision_max =  4             # set it between 0 to max-vision
rich_vision_max = 15              # set it between 0 to max-vision

# uneducated:0, primary education: 25, secondary education:50, tertiary education:75, graduate:100
poor_education_max   =  50           
middle_education_max =  75
rich_education_max   =  100

initial_wealth = 10


# inheritance tax
highest_thres_max_wealth = 4     # set in between 1 to 13
inheritance_threshold = 140      # set it between 80 to 140 with 10 increment size
flat_inh_tax = 50                # set it between 20 to 50 with 5 increment size
no_tax_slabs = 2                 # set it between 2 to 6
max_prog_inh_tax = 50            # set it between 0 to 50 with 5 increment size


number_of_ticks = 1500