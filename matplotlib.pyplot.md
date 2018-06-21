# General Setting
* define the figure size (h, w)  
  *plt.figure(figsize=(h, w))*
* set background grid  
  *plt.grid(True)*
* set the x, y lim  
  *plt.xlim(x_low, x_up)*  
  *plt.ylim(y_low, y_up)*
* set plot scale  
  *plt.xscale()*  
  *plt.yscale()*  
  *avaialbe tag: 'linear', 'log', 'logit', 'symlog'*  
* set x, y label  
  *plt.xlabel('x_label)*  
  *plt.ylabel('y_label)*
* set plot title  
  *plt.title('title')*

# 1D plot
* plot 1D data, while x and y list  
  *plt.plot(x,y)*
* plot [style](https://matplotlib.org/api/_as_gen/matplotlib.pyplot.plot.html)  
  *plt.plot(x,y, color=str, marker=str, linestyle=str, linewidth=int, markersize=int)*
