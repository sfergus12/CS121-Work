
```r

plot(1:2, type = "n", xlim = c(1, 100), ylim = c(1, 100), xlab = "", ylab = "")
angles <- seq(0, 2 * pi, length = 1000)
polygon(50 + 25 * cos(angles), 50 + 25 * sin(angles), col = "#99CCFF50", border = "NA")
polygon(25 + 16 * cos(angles), 67 + 28 * sin(angles), col = "#CC99FF50", border = "NA")
polygon(25 + 16 * cos(angles), 67 + 28 * sin(angles), col = "#CC99FF50", border = "NA")
polygon(c(15, 43, 43, 14), c(39, 39, 67, 67), col = "#00FF0060", border = "#0000FF60", 
    lwd = 8)
polygon(c(15, 43, 43, 14), c(39, 39, 67, 67), col = "#00FF0060", border = "#0000FF60", 
    lwd = 8)
polygon(c(15, 43, 43, 14), c(39, 39, 67, 67), col = "#00FF0060", border = "#0000FF60", 
    lwd = 8)
polygon(c(15, 43, 43, 14), c(39, 39, 67, 67), col = "#00FF0060", border = "#0000FF60")
polygon(c(27, 43, 43, 27), c(18, 18, 34, 34), col = "#FF3300", border = "#003300")
polygon(c(27, 43, 43, 27), c(18, 18, 34, 34), col = "#FF3300", border = "#003300")
polygon(c(27, 43, 43, 27), c(18, 18, 34, 34), col = "#FF3300", border = "#003300")
polygon(c(63, 84, 93, 74, 55), c(40, 40, 62, 75, 62), col = "#FFFF0050", border = "NA")
polygon(c(63, 84, 93, 74, 55), c(40, 40, 62, 75, 62), col = "#FFFF0050", border = "NA")
polygon(c(63, 84, 93, 74, 55), c(40, 40, 62, 75, 62), col = "#FFFF0050", border = "NA")
```

![plot of chunk unnamed-chunk-1](figure/unnamed-chunk-1.png) 

