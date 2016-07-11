# Getting Started with Phaser

This guide is a basic introduction to Phaser. The goal is to help you avoid some of the mistakes that previous cohorts have made in their journey to create their front-end capstones. As you design your game and discover things that would be helpful to include in this guide I hope that you will contribute by opening an issue on Github.

![Phaser_Guide](https://raw.githubusercontent.com/Jessicashinjo/Phaser_Guide/master/Images/Phaser_Map.png)

## Terms to know
 - Sprite- A computer graphic that can be moved and animated. This is usually created by having multiple frames on a spritesheet.
 - Body- This is an invisible object attached to your sprite. Physics will be applied to your sprite using the body.
 - [Group](http://phaser.io/docs/2.6.0/Phaser.Group.html) - Multiple of the same sprite. The same physics can be applied to the entire group.
 - Asset - Anything that you add to your game. For example: Artwork and audio.
 - Physics Engine - It allows your player to run, jump, fall, etc through velocity and gravity. It is also what detects collision between 2 objects in your game. In advanced physics engines you can even have your player swing on ropes.

## Physics Engines

Picking the right physics engine for your game is one of the most important things you will do. You should use the Physics Arcade engine unless you have special circumstances. Physics Arcade can do almost anything you will need and the docs/examples are extensive. Below is an explanation of the differences between Physics Arcade and P2 Physics.

#### [Physics Arcade](http://phaser.io/docs/2.6.0/Phaser.Physics.Arcade.html)
 - Easier to use than P2 with easy to understand documentation and numerous examples.
 - Uses plain English to describe physics.
 - The body of a sprite is represented by an invisible box. You can increase or decrease the size of the box but it will always be a box and not the outline of your sprite.
 - You can do everything but extremely complex physics.

#### [P2 Physics](http://phaser.io/docs/2.6.0/Phaser.Physics.P2.html)
 - More difficult to use than the Physics Arcade and the documentation is weaker.
 - Uses actual physics terminology like "Kinematic" instead of plain terms like "immovable" which requires you know the terminology to find the documentation.
 - The body of a sprite can be represented by the actual outline of the sprite using the Physics Editor program.
 - Can use complex physics. For example: Pendulum, rope, etc

## External Programs to Utilize
##### [Tiled](http://www.mapeditor.org/) (Arcade or P2)
 - This is a program that allows you to map out entire levels using your assets. Perfect for any type of game where you have a set level and your world is not randomly generated.

##### [Texture Packer](https://www.codeandweb.com/texturepacker) (Arcade or P2)
 - Allows you to create a sprite sheet from a set of images. This program is free as long as you uncheck all of the "Pro Version" items that are automatically selected. This is highly recommend for creating your sprites if you are not good with Photo Shop, Adobe Illustrator, etc.

##### [Physics Editor](https://www.codeandweb.com/physicseditor) (P2 only)
 - If you are using P2 Physics this program will allow you to draw the exact shape of the body that you want. This means you could have a banana for players to collect with the actual shape of a banana instead of the body being a box.

## Helpful Links
 - [Phaser Docs](http://phaser.io/docs/2.6.0/index)
 - [Flappy Bird tutorial](http://www.lessmilk.com/tutorial/flappy-bird-phaser-1) (Try out this tutorial first)
 - [General Phaser tutorials](https://www.youtube.com/channel/UCv0j-6tXIlnxmOu9FA3qFtw)
 - [Kenney's Assets](http://kenney.nl/assets) (Free if you download packs 1 at a time)
 - [Gameart2D](http://www.gameart2d.com/freebies.html) (Free assets)
 - [Open Game Art](http://opengameart.org/) (Free general game assets)

## Previous Cohort Games

##### William Hickok
- Game: [PhonX Rave](http://phonxrave.herokuapp.com/)
- Code: [PhonX Rave Code](https://github.com/williamhickok11/Front_End_Capstone)

##### Luke Lancaster
- Game: [Coffee Dude](http://www.luketlancaster.com/coffeedude/)
- Code: [Coffee Dude Code](https://github.com/luketlancaster/coffeedude)

##### Ryan Tanay
- Game: [Protein Panic](http://proteinpanic.newevolution.org/#/)
- Code: [Protein Panic Code](https://github.com/NewEvolution/proteinpanic)
