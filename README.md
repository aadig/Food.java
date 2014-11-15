Food.java
=========
package ArrayFun;

import zen.core.Zen;

public class Food {

	int x;
	int y;

	public Food() {

		x = 10 * Zen.getRandomNumber(1, 49);
		y = 10 * Zen.getRandomNumber(1, 49);
	}



	public void draw() {
		Zen.setColor("purple");
		Zen.fillOval(x, y, 10, 10);
	}
}
