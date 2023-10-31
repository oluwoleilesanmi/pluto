<div align="center">
    <h1>
        <a>Pluto</a>
    </h1>
    Visualization library for <i>easier plotting</i> built on top of Seaborn and Matplotlib.
</div>
<div padding-top=0.5em, padding-bottom=0, align="center">

[![Email Badge](https://img.shields.io/badge/-Gmail-D14836?style=flat&logo=gmail&logoColor=white)](mailto:oluwoleilesanmi@gmail.com)
[![LinkedIn Badge](https://img.shields.io/badge/LinkedIn-0077B5?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/oluwoleilesanmi)
[![GitHub Badge](https://img.shields.io/badge/GitHub-100000?style=flat&logo=github&logoColor=white)](https://github.com/oluwoleilesanmi)

</div>
<hr style="padding:0; margin:0;">

#### How to run
```
$ pip install pluto
```

```
# create custom bar_plot
bar_plot = Barplot()
# configuring custom bar_plot
bar_plot.shape(dim=(10, 5))
    .create('x_col', 'y_col', table, hue='z_col', c=None)
    .grid()
    .spine()
    .tick(left=True, labelleft=True, bottom=True, labelbottom=True)
    .label('x axis', 'y axis', 'title')
    .render()

```
#### Illustrations
- *TBI*

