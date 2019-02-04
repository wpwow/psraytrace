# psraytrace
Raytracing algorithm for one-way travel-time calculation in passive seismic or microseismic applications. Written in Python3. 
* shooting( ) - the core function of raytracing algorithm, actually a 2d algorithm
* psraytrace( ) - the core function to call shooting function and adapt it to 3D case. Unlike calculating two-way travel-time in reflection seismic raytracing program, only one-way travel-time for transmimitted P- or S-waves is calculated. You may modify this code to calculate the PS wave travel-time.

## Usage
psraytrace can be used as a module by simply importing the core function contained in folder [psmodules]. 

You may refer to the two examples with demo data, i.e. example2d.py and example3d.py included in folder [examples] for how to use the core function and may adapt to your case by modifying these examples. 

To run this program from source codes, you need to import the following dependencies:
* Matplotlib
* Pandas

By runing the main.py script, you would have the following images displayed.  
2D raytracing example  
![2D Example](https://github.com/uqzzhao/psraytrace/blob/master/examples/images/example2d.png)  
3D raytracing example  
![3D Example](https://github.com/uqzzhao/psraytrace/blob/master/examples/images/example3d.png)  


## License
MIT License.

## Authorship
psraytrace was written in 2016. The sole contributor is [Zhengguang Zhao](https://www.researchgate.net/profile/Zhengguang_Zhao2), who now works for DeepListen on part-time basis.
