Add your answers to the Algorithms exercises here.
# Exercise I
a) O(n)
b) O(n^3), because O(n)*O(n)*O(n)*10
c) O(n)


# Exercise II 

_n_ = building_height_in_stories
eggs = lots
egg_break_threshold_floor = _f_

*Assuming that lots of eggs means infinite (whole) eggs I'll assume it to be all possible positive intergers.*
set variable current_floor = 1
set variable egg_break_threshold_floor as _f_ = None
def egg_drop (current_floor, _n_):
    For each floor in range (current_floor, _n_+1):
        drop one egg,
        if egg doesn't crack:
            current_floor += 1
        elseif egg does crack: 
            _f_ = current_floor
            return _f_   

starting_floor = n / 2
take_height=
drop height



Well..... may work better to partition, sample, and drop...
but the runtime complexity of this current solution is linear O(n)
