Documentation
=============
*This is how it looks ...*

UI\Point
========
*A value object representing a point (co-ordinates) on the screen (x,y)*

```
class UI\Point {
	public double $x;
	public double $y;

	public function setX(double $x) : void;
	public function setY(double $y) : void;
	public function getX() : double;
	public function getY() : double;
}
```