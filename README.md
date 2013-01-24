3D Pie Chart
============

- Vector-based
- MIT licence

Example
-------

```
Raphael('canvas', 700, 500).pie({
	values: [87, 134, 83, 23, 98],
	colors: ["#00ff00", "#ff0011", "#faf600", "#0079fa", "#fa8500"],
	tooltip: ["January - 87", "Feburary - 136", "March - 77", "April - 120","May - 34"],
	doughnut: true,
	radius: 200,
	chartTitle: "Monthly Payment"
});
```

Options
-------
* values
* colors
* tooltip: tooltip for each slice
* doughnut: pie chart [false] || doughnut chart [true]
* radius
* chartTitle

![Doughnut chart](https://raw.github.com/PuffyCoffee/3D-Pie-chart/master/screenshot/doughnut.png "Doughnut Chart")

![Pie chart](https://raw.github.com/PuffyCoffee/3D-Pie-chart/master/screenshot/pie.png "Pie Chart")

-------

Peng Zhang 2012