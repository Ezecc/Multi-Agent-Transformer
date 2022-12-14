**.**
├── **images**
│   ├── **27m\_vs\_30m.gif**
│   ├── **3s5z\_vs\_3s6z.gif**
│   ├── **6h\_vs\_8z.gif**
│   ├── **arch.gif**
│   ├── **data.gif**
│   ├── **envs.png**
│   ├── **few\_shot.jpeg**
│   ├── **few\_shot\_smac.jpeg**
│   ├── **football.jpeg**
│   ├── **math.png**
│   ├── **MMM2.gif**
│   ├── **mujoco.png**
│   ├── **paradigm.jpeg**
│   └── **performance.jpeg**
├── install\_sc2.sh
├── **mat**
│   ├── **algorithms**
│   │   ├── \_\_init\_\_.py
│   │   ├── **mat**
│   │   │   ├── **algorithm**
│   │   │   │   ├── mat\_decoder.py
│   │   │   │   ├── mat\_encoder.py
│   │   │   │   ├── mat\_gru.py
│   │   │   │   ├── ma\_transformer.py
│   │   │   │   └── transformer\_policy.py
│   │   │   ├── \_\_init\_\_.py
│   │   │   └── mat\_trainer.py
│   │   └── **utils**
│   │       ├── transformer\_act.py
│   │       └── util.py
│   ├── config.py
│   ├── **envs**
│   │   ├── **dexteroushandenvs**
│   │   │   ├── **assets**
│   │   │   │   ├── **mjcf**
│   │   │   │   │   ├── **bottle\_cap**
│   │   │   │   │   │   ├── bounding\_box.json
│   │   │   │   │   │   ├── **images**
│   │   │   │   │   │   │   ├── **texture\_0.jpg**
│   │   │   │   │   │   │   └── **texture\_1.jpg**
│   │   │   │   │   │   ├── meta.json
│   │   │   │   │   │   ├── mobility.urdf
│   │   │   │   │   │   ├── mobility\_v2.json
│   │   │   │   │   │   ├── **parts\_render**
│   │   │   │   │   │   │   ├── **0.png**
│   │   │   │   │   │   │   ├── 0.txt
│   │   │   │   │   │   │   ├── **1.png**
│   │   │   │   │   │   │   ├── 1.txt
│   │   │   │   │   │   │   ├── **5.png**
│   │   │   │   │   │   │   ├── 5.txt
│   │   │   │   │   │   │   ├── **6.png**
│   │   │   │   │   │   │   ├── 6.txt
│   │   │   │   │   │   │   ├── **7.png**
│   │   │   │   │   │   │   └── 7.txt
│   │   │   │   │   │   ├── **parts\_render\_after\_merging**
│   │   │   │   │   │   │   ├── **0.png**
│   │   │   │   │   │   │   ├── 0.txt
│   │   │   │   │   │   │   ├── **1.png**
│   │   │   │   │   │   │   ├── 1.txt
│   │   │   │   │   │   │   ├── **2.png**
│   │   │   │   │   │   │   ├── 2.txt
│   │   │   │   │   │   │   ├── **3.png**
│   │   │   │   │   │   │   ├── 3.txt
│   │   │   │   │   │   │   ├── **4.png**
│   │   │   │   │   │   │   └── 4.txt
│   │   │   │   │   │   ├── **point\_sample**
│   │   │   │   │   │   │   ├── label-10000.txt
│   │   │   │   │   │   │   ├── ply-10000.ply
│   │   │   │   │   │   │   ├── pts-10000.pts
│   │   │   │   │   │   │   ├── pts-10000.txt
│   │   │   │   │   │   │   ├── sample-points-all-label-10000.txt
│   │   │   │   │   │   │   ├── sample-points-all-pts-label-10000.ply
│   │   │   │   │   │   │   ├── sample-points-all-pts-nor-rgba-10000.ply
│   │   │   │   │   │   │   └── sample-points-all-pts-nor-rgba-10000.txt
│   │   │   │   │   │   ├── result\_after\_merging.json
│   │   │   │   │   │   ├── result.json
│   │   │   │   │   │   ├── semantics.txt
│   │   │   │   │   │   ├── **textured\_objs**
│   │   │   │   │   │   │   ├── original-2.mtl
│   │   │   │   │   │   │   ├── original-2.obj
│   │   │   │   │   │   │   ├── original-3.mtl
│   │   │   │   │   │   │   ├── original-3.obj
│   │   │   │   │   │   │   ├── original-4.mtl
│   │   │   │   │   │   │   ├── original-4.obj
│   │   │   │   │   │   │   ├── original-5.mtl
│   │   │   │   │   │   │   ├── original-5.obj
│   │   │   │   │   │   │   ├── original-6.mtl
│   │   │   │   │   │   │   ├── original-6.obj
│   │   │   │   │   │   │   ├── original-7.mtl
│   │   │   │   │   │   │   ├── original-7.obj
│   │   │   │   │   │   │   ├── original-8.mtl
│   │   │   │   │   │   │   └── original-8.obj
│   │   │   │   │   │   ├── tree\_hier\_after\_merging.html
│   │   │   │   │   │   └── tree\_hier.html
│   │   │   │   │   ├── **bucket**
│   │   │   │   │   │   ├── **100454**
│   │   │   │   │   │   │   ├── bounding\_box.json
│   │   │   │   │   │   │   ├── **images**
│   │   │   │   │   │   │   │   └── **texture\_0.jpg**
│   │   │   │   │   │   │   ├── meta.json
│   │   │   │   │   │   │   ├── mobility.urdf
│   │   │   │   │   │   │   ├── mobility\_v2.json
│   │   │   │   │   │   │   ├── result.json
│   │   │   │   │   │   │   ├── result\_original.json
│   │   │   │   │   │   │   ├── semantics.txt
│   │   │   │   │   │   │   └── **textured\_objs**
│   │   │   │   │   │   │       ├── original-1.mtl
│   │   │   │   │   │   │       ├── original-1.obj
│   │   │   │   │   │   │       ├── original-2.mtl
│   │   │   │   │   │   │       └── original-2.obj
│   │   │   │   │   │   ├── bounding\_box.json
│   │   │   │   │   │   ├── **images**
│   │   │   │   │   │   │   ├── **texture\_0.jpg**
│   │   │   │   │   │   │   └── **texture\_1.jpg**
│   │   │   │   │   │   ├── meta.json
│   │   │   │   │   │   ├── mobility.urdf
│   │   │   │   │   │   ├── mobility\_v2.json
│   │   │   │   │   │   ├── result.json
│   │   │   │   │   │   ├── result\_original.json
│   │   │   │   │   │   ├── semantics.txt
│   │   │   │   │   │   └── **textured\_objs**
│   │   │   │   │   │       ├── original-10.mtl
│   │   │   │   │   │       ├── original-10.obj
│   │   │   │   │   │       ├── original-11.mtl
│   │   │   │   │   │       ├── original-11.obj
│   │   │   │   │   │       ├── original-13.mtl
│   │   │   │   │   │       ├── original-13.obj
│   │   │   │   │   │       ├── original-14.mtl
│   │   │   │   │   │       ├── original-14.obj
│   │   │   │   │   │       ├── original-1.mtl
│   │   │   │   │   │       ├── original-1.obj
│   │   │   │   │   │       ├── original-2.mtl
│   │   │   │   │   │       ├── original-2.obj
│   │   │   │   │   │       ├── original-3.mtl
│   │   │   │   │   │       ├── original-3.obj
│   │   │   │   │   │       ├── original-4.mtl
│   │   │   │   │   │       ├── original-4.obj
│   │   │   │   │   │       ├── original-5.mtl
│   │   │   │   │   │       ├── original-5.obj
│   │   │   │   │   │       ├── original-6.mtl
│   │   │   │   │   │       ├── original-6.obj
│   │   │   │   │   │       ├── original-7.mtl
│   │   │   │   │   │       ├── original-7.obj
│   │   │   │   │   │       ├── original-8.mtl
│   │   │   │   │   │       └── original-8.obj
│   │   │   │   │   ├── **cup**
│   │   │   │   │   │   ├── bounding\_box.json
│   │   │   │   │   │   ├── meta.json
│   │   │   │   │   │   ├── mobility.urdf
│   │   │   │   │   │   ├── mobility\_v2.json
│   │   │   │   │   │   ├── **parts\_render**
│   │   │   │   │   │   │   ├── **0.png**
│   │   │   │   │   │   │   ├── 0.txt
│   │   │   │   │   │   │   ├── **1.png**
│   │   │   │   │   │   │   ├── 1.txt
│   │   │   │   │   │   │   ├── **2.png**
│   │   │   │   │   │   │   ├── 2.txt
│   │   │   │   │   │   │   ├── **3.png**
│   │   │   │   │   │   │   └── 3.txt
│   │   │   │   │   │   ├── **parts\_render\_after\_merging**
│   │   │   │   │   │   │   ├── **0.png**
│   │   │   │   │   │   │   ├── 0.txt
│   │   │   │   │   │   │   ├── **1.png**
│   │   │   │   │   │   │   ├── 1.txt
│   │   │   │   │   │   │   ├── **2.png**
│   │   │   │   │   │   │   └── 2.txt
│   │   │   │   │   │   ├── **point\_sample**
│   │   │   │   │   │   │   ├── label-10000.txt
│   │   │   │   │   │   │   ├── ply-10000.ply
│   │   │   │   │   │   │   ├── pts-10000.pts
│   │   │   │   │   │   │   ├── pts-10000.txt
│   │   │   │   │   │   │   ├── sample-points-all-label-10000.txt
│   │   │   │   │   │   │   ├── sample-points-all-pts-label-10000.ply
│   │   │   │   │   │   │   ├── sample-points-all-pts-nor-rgba-10000.ply
│   │   │   │   │   │   │   └── sample-points-all-pts-nor-rgba-10000.txt
│   │   │   │   │   │   ├── result\_after\_merging.json
│   │   │   │   │   │   ├── result.json
│   │   │   │   │   │   ├── semantics.txt
│   │   │   │   │   │   ├── **textured\_objs**
│   │   │   │   │   │   │   ├── new-0.mtl
│   │   │   │   │   │   │   ├── new-0.obj
│   │   │   │   │   │   │   ├── new-1.mtl
│   │   │   │   │   │   │   ├── new-1.obj
│   │   │   │   │   │   │   ├── original-1.mtl
│   │   │   │   │   │   │   ├── original-1.obj
│   │   │   │   │   │   │   ├── original-2.mtl
│   │   │   │   │   │   │   ├── original-2.obj
│   │   │   │   │   │   │   ├── original-4.mtl
│   │   │   │   │   │   │   ├── original-4.obj
│   │   │   │   │   │   │   ├── original-5.mtl
│   │   │   │   │   │   │   ├── original-5.obj
│   │   │   │   │   │   │   ├── original-6.mtl
│   │   │   │   │   │   │   └── original-6.obj
│   │   │   │   │   │   ├── tree\_hier\_after\_merging.html
│   │   │   │   │   │   └── tree\_hier.html
│   │   │   │   │   ├── **door**
│   │   │   │   │   │   ├── bounding\_box.json
│   │   │   │   │   │   ├── **images**
│   │   │   │   │   │   │   └── **texture\_0.jpg**
│   │   │   │   │   │   ├── meta.json
│   │   │   │   │   │   ├── mobility.urdf
│   │   │   │   │   │   ├── mobility\_v2.json
│   │   │   │   │   │   ├── **parts\_render**
│   │   │   │   │   │   │   ├── **0.png**
│   │   │   │   │   │   │   ├── 0.txt
│   │   │   │   │   │   │   ├── **1.png**
│   │   │   │   │   │   │   ├── 1.txt
│   │   │   │   │   │   │   ├── **23.png**
│   │   │   │   │   │   │   ├── 23.txt
│   │   │   │   │   │   │   ├── **24.png**
│   │   │   │   │   │   │   ├── 24.txt
│   │   │   │   │   │   │   ├── **25.png**
│   │   │   │   │   │   │   ├── 25.txt
│   │   │   │   │   │   │   ├── **26.png**
│   │   │   │   │   │   │   ├── 26.txt
│   │   │   │   │   │   │   ├── **27.png**
│   │   │   │   │   │   │   ├── 27.txt
│   │   │   │   │   │   │   ├── **28.png**
│   │   │   │   │   │   │   ├── 28.txt
│   │   │   │   │   │   │   ├── **29.png**
│   │   │   │   │   │   │   ├── 29.txt
│   │   │   │   │   │   │   ├── **2.png**
│   │   │   │   │   │   │   ├── 2.txt
│   │   │   │   │   │   │   ├── **30.png**
│   │   │   │   │   │   │   ├── 30.txt
│   │   │   │   │   │   │   ├── **31.png**
│   │   │   │   │   │   │   ├── 31.txt
│   │   │   │   │   │   │   ├── **32.png**
│   │   │   │   │   │   │   ├── 32.txt
│   │   │   │   │   │   │   ├── **33.png**
│   │   │   │   │   │   │   ├── 33.txt
│   │   │   │   │   │   │   ├── **34.png**
│   │   │   │   │   │   │   └── 34.txt
│   │   │   │   │   │   ├── **parts\_render\_after\_merging**
│   │   │   │   │   │   │   ├── **0.png**
│   │   │   │   │   │   │   ├── 0.txt
│   │   │   │   │   │   │   ├── **10.png**
│   │   │   │   │   │   │   ├── 10.txt
│   │   │   │   │   │   │   ├── **11.png**
│   │   │   │   │   │   │   ├── 11.txt
│   │   │   │   │   │   │   ├── **12.png**
│   │   │   │   │   │   │   ├── 12.txt
│   │   │   │   │   │   │   ├── **1.png**
│   │   │   │   │   │   │   ├── 1.txt
│   │   │   │   │   │   │   ├── **2.png**
│   │   │   │   │   │   │   ├── 2.txt
│   │   │   │   │   │   │   ├── **3.png**
│   │   │   │   │   │   │   ├── 3.txt
│   │   │   │   │   │   │   ├── **4.png**
│   │   │   │   │   │   │   ├── 4.txt
│   │   │   │   │   │   │   ├── **5.png**
│   │   │   │   │   │   │   ├── 5.txt
│   │   │   │   │   │   │   ├── **6.png**
│   │   │   │   │   │   │   ├── 6.txt
│   │   │   │   │   │   │   ├── **7.png**
│   │   │   │   │   │   │   ├── 7.txt
│   │   │   │   │   │   │   ├── **8.png**
│   │   │   │   │   │   │   ├── 8.txt
│   │   │   │   │   │   │   ├── **9.png**
│   │   │   │   │   │   │   └── 9.txt
│   │   │   │   │   │   ├── **point\_sample**
│   │   │   │   │   │   │   ├── label-10000.txt
│   │   │   │   │   │   │   ├── ply-10000.ply
│   │   │   │   │   │   │   ├── pts-10000.pts
│   │   │   │   │   │   │   ├── pts-10000.txt
│   │   │   │   │   │   │   ├── sample-points-all-label-10000.txt
│   │   │   │   │   │   │   ├── sample-points-all-pts-label-10000.ply
│   │   │   │   │   │   │   ├── sample-points-all-pts-nor-rgba-10000.ply
│   │   │   │   │   │   │   └── sample-points-all-pts-nor-rgba-10000.txt
│   │   │   │   │   │   ├── result\_after\_merging.json
│   │   │   │   │   │   ├── result.json
│   │   │   │   │   │   ├── semantics.txt
│   │   │   │   │   │   ├── **textured\_objs**
│   │   │   │   │   │   │   ├── original-10.mtl
│   │   │   │   │   │   │   ├── original-10.obj
│   │   │   │   │   │   │   ├── original-11.mtl
│   │   │   │   │   │   │   ├── original-11.obj
│   │   │   │   │   │   │   ├── original-12.mtl
│   │   │   │   │   │   │   ├── original-12.obj
│   │   │   │   │   │   │   ├── original-1.mtl
│   │   │   │   │   │   │   ├── original-1.obj
│   │   │   │   │   │   │   ├── original-2.mtl
│   │   │   │   │   │   │   ├── original-2.obj
│   │   │   │   │   │   │   ├── original-5.mtl
│   │   │   │   │   │   │   ├── original-5.obj
│   │   │   │   │   │   │   ├── original-6.mtl
│   │   │   │   │   │   │   ├── original-6.obj
│   │   │   │   │   │   │   ├── original-7.mtl
│   │   │   │   │   │   │   └── original-7.obj
│   │   │   │   │   │   ├── tree\_hier\_after\_merging.html
│   │   │   │   │   │   └── tree\_hier.html
│   │   │   │   │   ├── **kettle**
│   │   │   │   │   │   ├── bounding\_box.json
│   │   │   │   │   │   ├── meta.json
│   │   │   │   │   │   ├── mobility.urdf
│   │   │   │   │   │   ├── mobility\_v2.json
│   │   │   │   │   │   ├── result.json
│   │   │   │   │   │   ├── result\_original.json
│   │   │   │   │   │   ├── semantics.txt
│   │   │   │   │   │   └── **textured\_objs**
│   │   │   │   │   │       ├── original-1.mtl
│   │   │   │   │   │       ├── original-1.obj
│   │   │   │   │   │       ├── original-2.mtl
│   │   │   │   │   │       ├── original-2.obj
│   │   │   │   │   │       ├── original-3.mtl
│   │   │   │   │   │       ├── original-3.obj
│   │   │   │   │   │       ├── original-4.mtl
│   │   │   │   │   │       └── original-4.obj
│   │   │   │   │   ├── **open\_ai\_assets**
│   │   │   │   │   │   ├── **fetch**
│   │   │   │   │   │   │   ├── **pick\_and\_place.xml**
│   │   │   │   │   │   │   ├── **push.xml**
│   │   │   │   │   │   │   ├── **reach.xml**
│   │   │   │   │   │   │   ├── **robot.xml**
│   │   │   │   │   │   │   ├── **shared.xml**
│   │   │   │   │   │   │   └── **slide.xml**
│   │   │   │   │   │   ├── **hand**
│   │   │   │   │   │   │   ├── **egg.xml**
│   │   │   │   │   │   │   ├── **manipulate\_block\_touch\_sensors.xml**
│   │   │   │   │   │   │   ├── **manipulate\_block.xml**
│   │   │   │   │   │   │   ├── **manipulate\_egg\_touch\_sensors.xml**
│   │   │   │   │   │   │   ├── **manipulate\_egg.xml**
│   │   │   │   │   │   │   ├── **manipulate\_pen\_touch\_sensors.xml**
│   │   │   │   │   │   │   ├── **manipulate\_pen.xml**
│   │   │   │   │   │   │   ├── **pen.xml**
│   │   │   │   │   │   │   ├── **reach.xml**
│   │   │   │   │   │   │   ├── **robot1.xml**
│   │   │   │   │   │   │   ├── **robot\_touch\_sensors\_92.xml**
│   │   │   │   │   │   │   ├── **robot.xml**
│   │   │   │   │   │   │   ├── **shadow\_hand1.xml**
│   │   │   │   │   │   │   ├── **shadow\_hand.xml**
│   │   │   │   │   │   │   ├── **shared1.xml**
│   │   │   │   │   │   │   ├── **shared\_asset1.xml**
│   │   │   │   │   │   │   ├── **shared\_asset.xml**
│   │   │   │   │   │   │   ├── **shared\_touch\_sensors\_92.xml**
│   │   │   │   │   │   │   └── **shared.xml**
│   │   │   │   │   │   ├── **LICENSE.md**
│   │   │   │   │   │   ├── **stls**
│   │   │   │   │   │   │   ├── **fetch**
│   │   │   │   │   │   │   │   ├── **base\_link\_collision.stl**
│   │   │   │   │   │   │   │   ├── **bellows\_link\_collision.stl**
│   │   │   │   │   │   │   │   ├── **elbow\_flex\_link\_collision.stl**
│   │   │   │   │   │   │   │   ├── **estop\_link.stl**
│   │   │   │   │   │   │   │   ├── **forearm\_roll\_link\_collision.stl**
│   │   │   │   │   │   │   │   ├── **gripper\_link.stl**
│   │   │   │   │   │   │   │   ├── **head\_pan\_link\_collision.stl**
│   │   │   │   │   │   │   │   ├── **head\_tilt\_link\_collision.stl**
│   │   │   │   │   │   │   │   ├── **laser\_link.stl**
│   │   │   │   │   │   │   │   ├── **l\_wheel\_link\_collision.stl**
│   │   │   │   │   │   │   │   ├── **r\_wheel\_link\_collision.stl**
│   │   │   │   │   │   │   │   ├── **shoulder\_lift\_link\_collision.stl**
│   │   │   │   │   │   │   │   ├── **shoulder\_pan\_link\_collision.stl**
│   │   │   │   │   │   │   │   ├── **torso\_fixed\_link.stl**
│   │   │   │   │   │   │   │   ├── **torso\_lift\_link\_collision.stl**
│   │   │   │   │   │   │   │   ├── **upperarm\_roll\_link\_collision.stl**
│   │   │   │   │   │   │   │   ├── **wrist\_flex\_link\_collision.stl**
│   │   │   │   │   │   │   │   └── **wrist\_roll\_link\_collision.stl**
│   │   │   │   │   │   │   └── **hand**
│   │   │   │   │   │   │       ├── **F1.stl**
│   │   │   │   │   │   │       ├── **F2.stl**
│   │   │   │   │   │   │       ├── **F3.stl**
│   │   │   │   │   │   │       ├── **forearm\_electric\_cvx.stl**
│   │   │   │   │   │   │       ├── **forearm\_electric.stl**
│   │   │   │   │   │   │       ├── **knuckle.stl**
│   │   │   │   │   │   │       ├── **lfmetacarpal.stl**
│   │   │   │   │   │   │       ├── **palm.stl**
│   │   │   │   │   │   │       ├── **TH1\_z.stl**
│   │   │   │   │   │   │       ├── **TH2\_z.stl**
│   │   │   │   │   │   │       ├── **TH3\_z.stl**
│   │   │   │   │   │   │       └── **wrist.stl**
│   │   │   │   │   │   └── **textures**
│   │   │   │   │   │       ├── **block\_hidden.png**
│   │   │   │   │   │       └── **block.png**
│   │   │   │   │   ├── **pen**
│   │   │   │   │   │   ├── bounding\_box.json
│   │   │   │   │   │   ├── meta.json
│   │   │   │   │   │   ├── mobility.urdf
│   │   │   │   │   │   ├── mobility\_v2.json
│   │   │   │   │   │   ├── result.json
│   │   │   │   │   │   ├── result\_original.json
│   │   │   │   │   │   ├── semantics.txt
│   │   │   │   │   │   └── **textured\_objs**
│   │   │   │   │   │       ├── original-10.mtl
│   │   │   │   │   │       ├── original-10.obj
│   │   │   │   │   │       ├── original-11.mtl
│   │   │   │   │   │       ├── original-11.obj
│   │   │   │   │   │       ├── original-12.mtl
│   │   │   │   │   │       ├── original-12.obj
│   │   │   │   │   │       ├── original-13.mtl
│   │   │   │   │   │       ├── original-13.obj
│   │   │   │   │   │       ├── original-14.mtl
│   │   │   │   │   │       ├── original-14.obj
│   │   │   │   │   │       ├── original-15.mtl
│   │   │   │   │   │       ├── original-15.obj
│   │   │   │   │   │       ├── original-16.mtl
│   │   │   │   │   │       ├── original-16.obj
│   │   │   │   │   │       ├── original-17.mtl
│   │   │   │   │   │       ├── original-17.obj
│   │   │   │   │   │       ├── original-18.mtl
│   │   │   │   │   │       ├── original-18.obj
│   │   │   │   │   │       ├── original-19.mtl
│   │   │   │   │   │       ├── original-19.obj
│   │   │   │   │   │       ├── original-1.mtl
│   │   │   │   │   │       ├── original-1.obj
│   │   │   │   │   │       ├── original-2.mtl
│   │   │   │   │   │       ├── original-2.obj
│   │   │   │   │   │       ├── original-3.mtl
│   │   │   │   │   │       ├── original-3.obj
│   │   │   │   │   │       ├── original-4.mtl
│   │   │   │   │   │       ├── original-4.obj
│   │   │   │   │   │       ├── original-5.mtl
│   │   │   │   │   │       ├── original-5.obj
│   │   │   │   │   │       ├── original-6.mtl
│   │   │   │   │   │       ├── original-6.obj
│   │   │   │   │   │       ├── original-7.mtl
│   │   │   │   │   │       ├── original-7.obj
│   │   │   │   │   │       ├── original-8.mtl
│   │   │   │   │   │       ├── original-8.obj
│   │   │   │   │   │       ├── original-9.mtl
│   │   │   │   │   │       └── original-9.obj
│   │   │   │   │   ├── **pot**
│   │   │   │   │   │   ├── bounding\_box.json
│   │   │   │   │   │   ├── **images**
│   │   │   │   │   │   │   ├── **texture\_0.png**
│   │   │   │   │   │   │   ├── **texture\_1.jpg**
│   │   │   │   │   │   │   └── **texture\_2.jpg**
│   │   │   │   │   │   ├── meta.json
│   │   │   │   │   │   ├── mobility.urdf
│   │   │   │   │   │   ├── mobility\_v2.json
│   │   │   │   │   │   ├── mobilityWithoutCover.urdf
│   │   │   │   │   │   ├── pot.xml
│   │   │   │   │   │   ├── result.json
│   │   │   │   │   │   ├── result\_original.json
│   │   │   │   │   │   ├── semantics.txt
│   │   │   │   │   │   └── **textured\_objs**
│   │   │   │   │   │       ├── original-10.mtl
│   │   │   │   │   │       ├── original-10.obj
│   │   │   │   │   │       ├── original-11.mtl
│   │   │   │   │   │       ├── original-11.obj
│   │   │   │   │   │       ├── original-13.mtl
│   │   │   │   │   │       ├── original-13.obj
│   │   │   │   │   │       ├── original-14.mtl
│   │   │   │   │   │       ├── original-14.obj
│   │   │   │   │   │       ├── original-15.mtl
│   │   │   │   │   │       ├── original-15.obj
│   │   │   │   │   │       ├── original-16.mtl
│   │   │   │   │   │       ├── original-16.obj
│   │   │   │   │   │       ├── original-17.mtl
│   │   │   │   │   │       ├── original-17.obj
│   │   │   │   │   │       ├── original-19.mtl
│   │   │   │   │   │       ├── original-19.obj
│   │   │   │   │   │       ├── original-1.mtl
│   │   │   │   │   │       ├── original-1.obj
│   │   │   │   │   │       ├── original-21.mtl
│   │   │   │   │   │       ├── original-21.obj
│   │   │   │   │   │       ├── original-22.mtl
│   │   │   │   │   │       ├── original-22.obj
│   │   │   │   │   │       ├── original-23.mtl
│   │   │   │   │   │       ├── original-23.obj
│   │   │   │   │   │       ├── original-25.mtl
│   │   │   │   │   │       ├── original-25.obj
│   │   │   │   │   │       ├── original-26.mtl
│   │   │   │   │   │       ├── original-26.obj
│   │   │   │   │   │       ├── original-27.mtl
│   │   │   │   │   │       ├── original-27.obj
│   │   │   │   │   │       ├── original-29.mtl
│   │   │   │   │   │       ├── original-29.obj
│   │   │   │   │   │       ├── original-30.mtl
│   │   │   │   │   │       ├── original-30.obj
│   │   │   │   │   │       ├── original-31.mtl
│   │   │   │   │   │       ├── original-31.obj
│   │   │   │   │   │       ├── original-5.mtl
│   │   │   │   │   │       ├── original-5.obj
│   │   │   │   │   │       ├── original-6.mtl
│   │   │   │   │   │       ├── original-6.obj
│   │   │   │   │   │       ├── original-7.mtl
│   │   │   │   │   │       ├── original-7.obj
│   │   │   │   │   │       ├── original-8.mtl
│   │   │   │   │   │       └── original-8.obj
│   │   │   │   │   ├── **scissors**
│   │   │   │   │   │   └── **10495**
│   │   │   │   │   │       ├── bounding\_box.json
│   │   │   │   │   │       ├── meta.json
│   │   │   │   │   │       ├── mobility.urdf
│   │   │   │   │   │       ├── mobility\_v2.json
│   │   │   │   │   │       ├── **parts\_render**
│   │   │   │   │   │       │   ├── **0.png**
│   │   │   │   │   │       │   ├── 0.txt
│   │   │   │   │   │       │   ├── **1.png**
│   │   │   │   │   │       │   ├── 1.txt
│   │   │   │   │   │       │   ├── **2.png**
│   │   │   │   │   │       │   ├── 2.txt
│   │   │   │   │   │       │   ├── **3.png**
│   │   │   │   │   │       │   ├── 3.txt
│   │   │   │   │   │       │   ├── **4.png**
│   │   │   │   │   │       │   ├── 4.txt
│   │   │   │   │   │       │   ├── **5.png**
│   │   │   │   │   │       │   ├── 5.txt
│   │   │   │   │   │       │   ├── **6.png**
│   │   │   │   │   │       │   ├── 6.txt
│   │   │   │   │   │       │   ├── **7.png**
│   │   │   │   │   │       │   └── 7.txt
│   │   │   │   │   │       ├── **parts\_render\_after\_merging**
│   │   │   │   │   │       │   ├── **0.png**
│   │   │   │   │   │       │   ├── 0.txt
│   │   │   │   │   │       │   ├── **1.png**
│   │   │   │   │   │       │   ├── 1.txt
│   │   │   │   │   │       │   ├── **2.png**
│   │   │   │   │   │       │   ├── 2.txt
│   │   │   │   │   │       │   ├── **3.png**
│   │   │   │   │   │       │   ├── 3.txt
│   │   │   │   │   │       │   ├── **4.png**
│   │   │   │   │   │       │   ├── 4.txt
│   │   │   │   │   │       │   ├── **5.png**
│   │   │   │   │   │       │   ├── 5.txt
│   │   │   │   │   │       │   ├── **6.png**
│   │   │   │   │   │       │   ├── 6.txt
│   │   │   │   │   │       │   ├── **7.png**
│   │   │   │   │   │       │   └── 7.txt
│   │   │   │   │   │       ├── **point\_sample**
│   │   │   │   │   │       │   ├── label-10000.txt
│   │   │   │   │   │       │   ├── ply-10000.ply
│   │   │   │   │   │       │   ├── pts-10000.pts
│   │   │   │   │   │       │   ├── pts-10000.txt
│   │   │   │   │   │       │   ├── sample-points-all-label-10000.txt
│   │   │   │   │   │       │   ├── sample-points-all-pts-label-10000.ply
│   │   │   │   │   │       │   ├── sample-points-all-pts-nor-rgba-10000.ply
│   │   │   │   │   │       │   └── sample-points-all-pts-nor-rgba-10000.txt
│   │   │   │   │   │       ├── result\_after\_merging.json
│   │   │   │   │   │       ├── result.json
│   │   │   │   │   │       ├── semantics.txt
│   │   │   │   │   │       ├── **textured\_objs**
│   │   │   │   │   │       │   ├── new-0.mtl
│   │   │   │   │   │       │   ├── new-0.obj
│   │   │   │   │   │       │   ├── new-1.mtl
│   │   │   │   │   │       │   ├── new-1.obj
│   │   │   │   │   │       │   ├── new-2.mtl
│   │   │   │   │   │       │   ├── new-2.obj
│   │   │   │   │   │       │   ├── new-3.mtl
│   │   │   │   │   │       │   ├── new-3.obj
│   │   │   │   │   │       │   ├── original-3.mtl
│   │   │   │   │   │       │   ├── original-3.obj
│   │   │   │   │   │       │   ├── original-6.mtl
│   │   │   │   │   │       │   └── original-6.obj
│   │   │   │   │   │       ├── tree\_hier\_after\_merging.html
│   │   │   │   │   │       └── tree\_hier.html
│   │   │   │   │   └── **switch**
│   │   │   │   │       ├── **102872**
│   │   │   │   │       │   ├── bounding\_box.json
│   │   │   │   │       │   ├── meta.json
│   │   │   │   │       │   ├── mobility.urdf
│   │   │   │   │       │   ├── mobility\_v2.json
│   │   │   │   │       │   ├── result.json
│   │   │   │   │       │   ├── result\_original.json
│   │   │   │   │       │   ├── semantics.txt
│   │   │   │   │       │   └── **textured\_objs**
│   │   │   │   │       │       ├── original-1.mtl
│   │   │   │   │       │       ├── original-1.obj
│   │   │   │   │       │       ├── original-2.mtl
│   │   │   │   │       │       ├── original-2.obj
│   │   │   │   │       │       ├── original-3.mtl
│   │   │   │   │       │       ├── original-3.obj
│   │   │   │   │       │       ├── original-4.mtl
│   │   │   │   │       │       ├── original-4.obj
│   │   │   │   │       │       ├── original-6.mtl
│   │   │   │   │       │       ├── original-6.obj
│   │   │   │   │       │       ├── original-7.mtl
│   │   │   │   │       │       ├── original-7.obj
│   │   │   │   │       │       ├── original-8.mtl
│   │   │   │   │       │       ├── original-8.obj
│   │   │   │   │       │       ├── original-9.mtl
│   │   │   │   │       │       └── original-9.obj
│   │   │   │   │       ├── bounding\_box.json
│   │   │   │   │       ├── meta.json
│   │   │   │   │       ├── mobility.urdf
│   │   │   │   │       ├── mobility\_v2.json
│   │   │   │   │       ├── result.json
│   │   │   │   │       ├── result\_original.json
│   │   │   │   │       ├── semantics.txt
│   │   │   │   │       └── **textured\_objs**
│   │   │   │   │           ├── original-10.mtl
│   │   │   │   │           ├── original-10.obj
│   │   │   │   │           ├── original-11.mtl
│   │   │   │   │           ├── original-11.obj
│   │   │   │   │           ├── original-12.mtl
│   │   │   │   │           ├── original-12.obj
│   │   │   │   │           ├── original-13.mtl
│   │   │   │   │           ├── original-13.obj
│   │   │   │   │           ├── original-14.mtl
│   │   │   │   │           ├── original-14.obj
│   │   │   │   │           ├── original-1.mtl
│   │   │   │   │           ├── original-1.obj
│   │   │   │   │           ├── original-2.mtl
│   │   │   │   │           ├── original-2.obj
│   │   │   │   │           ├── original-3.mtl
│   │   │   │   │           ├── original-3.obj
│   │   │   │   │           ├── original-4.mtl
│   │   │   │   │           ├── original-4.obj
│   │   │   │   │           ├── original-5.mtl
│   │   │   │   │           ├── original-5.obj
│   │   │   │   │           ├── original-6.mtl
│   │   │   │   │           ├── original-6.obj
│   │   │   │   │           ├── original-7.mtl
│   │   │   │   │           ├── original-7.obj
│   │   │   │   │           ├── original-8.mtl
│   │   │   │   │           ├── original-8.obj
│   │   │   │   │           ├── original-9.mtl
│   │   │   │   │           └── original-9.obj
│   │   │   │   ├── **textures**
│   │   │   │   │   ├── **background\_texture\_metal\_rust.jpg**
│   │   │   │   │   ├── **metal\_wall\_iron\_fence.jpg**
│   │   │   │   │   ├── **particle\_board\_paint\_aged.jpg**
│   │   │   │   │   ├── **pebble\_stone\_texture\_nature.jpg**
│   │   │   │   │   ├── **texture\_background\_wall\_paint\_2.jpg**
│   │   │   │   │   ├── **texture\_background\_wall\_paint\_3.jpg**
│   │   │   │   │   ├── **texture\_stone\_stone\_texture\_0.jpg**
│   │   │   │   │   └── **texture\_wood\_brown\_1033760.jpg**
│   │   │   │   └── **urdf**
│   │   │   │       ├── **ball.urdf**
│   │   │   │       ├── **cartpole.urdf**
│   │   │   │       ├── **cube.urdf**
│   │   │   │       ├── **icosphere.tet**
│   │   │   │       ├── **icosphere.urdf**
│   │   │   │       ├── **objects**
│   │   │   │       │   ├── **ball.urdf**
│   │   │   │       │   ├── **cube\_goal\_multicolor.urdf**
│   │   │   │       │   ├── **cube\_multicolor1.urdf**
│   │   │   │       │   ├── **cube\_multicolor.urdf**
│   │   │   │       │   └── **meshes**
│   │   │   │       │       ├── **ball.obj**
│   │   │   │       │       ├── **ball.stl**
│   │   │   │       │       ├── **cube\_multicolor.mtl**
│   │   │   │       │       └── **cube\_multicolor.obj**
│   │   │   │       ├── **shadow\_hand\_description**
│   │   │   │       │   ├── **meshes**
│   │   │   │       │   │   ├── **biotac\_decimated.dae**
│   │   │   │       │   │   ├── **biotac\_thumb\_adapter.dae**
│   │   │   │       │   │   ├── **convert\_dae2obj.py**
│   │   │   │       │   │   ├── **distal\_ellipsoid.dae**
│   │   │   │       │   │   ├── **distal\_ellipsoid.obj**
│   │   │   │       │   │   ├── **F1.dae**
│   │   │   │       │   │   ├── **F1.obj**
│   │   │   │       │   │   ├── **F2.dae**
│   │   │   │       │   │   ├── **F2.obj**
│   │   │   │       │   │   ├── **F3.dae**
│   │   │   │       │   │   ├── **F3.obj**
│   │   │   │       │   │   ├── **forearm.dae**
│   │   │   │       │   │   ├── **forearm\_muscle.dae**
│   │   │   │       │   │   ├── **forearm\_muscle.obj**
│   │   │   │       │   │   ├── **forearm.obj**
│   │   │   │       │   │   ├── **knuckle.dae**
│   │   │   │       │   │   ├── **knuckle.obj**
│   │   │   │       │   │   ├── **lfmetacarpal.dae**
│   │   │   │       │   │   ├── **lfmetacarpal.obj**
│   │   │   │       │   │   ├── **palm.dae**
│   │   │   │       │   │   ├── **palm.obj**
│   │   │   │       │   │   ├── **TH1\_z.dae**
│   │   │   │       │   │   ├── **TH1\_z.obj**
│   │   │   │       │   │   ├── **TH2\_z.dae**
│   │   │   │       │   │   ├── **TH2\_z.obj**
│   │   │   │       │   │   ├── **TH3\_z.dae**
│   │   │   │       │   │   ├── **TH3\_z.obj**
│   │   │   │       │   │   ├── **wrist.dae**
│   │   │   │       │   │   └── **wrist.obj**
│   │   │   │       │   ├── **shadowhand\_new.urdf**
│   │   │   │       │   ├── **shadowhand.urdf**
│   │   │   │       │   └── **shadowhand\_with\_fingertips.urdf**
│   │   │   │       ├── **small\_ball.urdf**
│   │   │   │       ├── **square\_table.urdf**
│   │   │   │       ├── **tray**
│   │   │   │       │   ├── **traybox.urdf**
│   │   │   │       │   ├── **tray.jpg**
│   │   │   │       │   ├── **tray\_textured2.mtl**
│   │   │   │       │   ├── **tray\_textured2.obj**
│   │   │   │       │   ├── **tray\_textured2.urdf**
│   │   │   │       │   ├── **tray\_textured4.mtl**
│   │   │   │       │   ├── **tray\_textured4.obj**
│   │   │   │       │   ├── **tray\_textured.mtl**
│   │   │   │       │   ├── **tray\_textured.obj**
│   │   │   │       │   └── **tray.urdf**
│   │   │   │       └── **ycb**
│   │   │   │           ├── **010\_potted\_meat\_can**
│   │   │   │           │   ├── **010\_potted\_meat\_can.urdf**
│   │   │   │           │   ├── **collision.obj**
│   │   │   │           │   ├── **MI\_010\_potted\_meat\_can\_MI\_010\_potted\_meat\_can\_D.png**
│   │   │   │           │   ├── **textured.mtl**
│   │   │   │           │   └── **textured.obj**
│   │   │   │           ├── **011\_banana**
│   │   │   │           │   ├── **011\_banana.urdf**
│   │   │   │           │   ├── **collision.obj**
│   │   │   │           │   ├── **MI\_011\_banana\_MI\_011\_banana\_D.png**
│   │   │   │           │   ├── **textured.mtl**
│   │   │   │           │   └── **textured.obj**
│   │   │   │           ├── **025\_mug**
│   │   │   │           │   ├── **025\_mug.urdf**
│   │   │   │           │   ├── **MI\_025\_mug\_MI\_025\_mug\_D.png**
│   │   │   │           │   ├── **mug\_collision.obj**
│   │   │   │           │   ├── **mug\_collision\_tw.obj**
│   │   │   │           │   ├── **mug\_collision\_vhacd.obj**
│   │   │   │           │   ├── **mug\_visual.obj**
│   │   │   │           │   ├── **textured.mtl**
│   │   │   │           │   └── **textured.obj**
│   │   │   │           └── **061\_foam\_brick**
│   │   │   │               ├── **061\_foam\_brick.urdf**
│   │   │   │               ├── **MI\_061\_foam\_brick\_MI\_061\_foam\_brick\_D.png**
│   │   │   │               ├── **textured.mtl**
│   │   │   │               └── **textured.obj**
│   │   │   ├── **cfg**
│   │   │   │   ├── **ddpg**
│   │   │   │   │   └── config.yaml
│   │   │   │   ├── franka\_cabinet.yaml
│   │   │   │   ├── **happo**
│   │   │   │   │   ├── config.yaml
│   │   │   │   │   └── lift\_config.yaml
│   │   │   │   ├── **hatrpo**
│   │   │   │   │   └── config.yaml
│   │   │   │   ├── humanoid.yaml
│   │   │   │   ├── **ippo**
│   │   │   │   │   └── config.yaml
│   │   │   │   ├── **maddpg**
│   │   │   │   │   └── config.yaml
│   │   │   │   ├── **mamlppo**
│   │   │   │   │   └── config.yaml
│   │   │   │   ├── **mappo**
│   │   │   │   │   ├── config.yaml
│   │   │   │   │   └── lift\_config.yaml
│   │   │   │   ├── **meta\_env\_cfg**
│   │   │   │   │   ├── shadow\_hand\_meta\_ml1.yaml
│   │   │   │   │   ├── shadow\_hand\_meta\_mt1.yaml
│   │   │   │   │   ├── shadow\_hand\_meta\_mt20.yaml
│   │   │   │   │   ├── shadow\_hand\_meta\_mt5\_door.yaml
│   │   │   │   │   ├── shadow\_hand\_meta\_mt5.yaml
│   │   │   │   │   └── shadow\_hand\_meta.yaml
│   │   │   │   ├── **mtppo**
│   │   │   │   │   └── config.yaml
│   │   │   │   ├── **mtsac**
│   │   │   │   │   └── config.yaml
│   │   │   │   ├── **mttrpo**
│   │   │   │   │   └── config.yaml
│   │   │   │   ├── **ppo**
│   │   │   │   │   ├── block\_config.yaml
│   │   │   │   │   ├── config.yaml
│   │   │   │   │   ├── humanoid\_config.yaml
│   │   │   │   │   └── lift\_config.yaml
│   │   │   │   ├── **sac**
│   │   │   │   │   ├── config.yaml
│   │   │   │   │   └── humanoid\_config.yaml
│   │   │   │   ├── shadow\_hand\_block\_stack.yaml
│   │   │   │   ├── shadow\_hand\_bottle\_cap.yaml
│   │   │   │   ├── shadow\_hand\_catch\_abreast.yaml
│   │   │   │   ├── shadow\_hand\_catch\_over2underarm.yaml
│   │   │   │   ├── shadow\_hand\_catch\_overarm.yaml
│   │   │   │   ├── shadow\_hand\_catch\_underarm.yaml
│   │   │   │   ├── shadow\_hand\_door\_close\_inward.yaml
│   │   │   │   ├── shadow\_hand\_door\_close\_outward.yaml
│   │   │   │   ├── shadow\_hand\_door\_open\_inward.yaml
│   │   │   │   ├── shadow\_hand\_door\_open\_outward.yaml
│   │   │   │   ├── shadow\_hand\_grasp\_and\_place.yaml
│   │   │   │   ├── shadow\_hand\_kettle.yaml
│   │   │   │   ├── shadow\_hand\_lift\_cup.yaml
│   │   │   │   ├── shadow\_hand\_lift\_overarm.yaml
│   │   │   │   ├── shadow\_hand\_lift\_underarm2.yaml
│   │   │   │   ├── shadow\_hand\_lift\_underarm.yaml
│   │   │   │   ├── shadow\_hand\_lift.yaml
│   │   │   │   ├── shadow\_hand\_over\_overarm.yaml
│   │   │   │   ├── shadow\_hand\_over.yaml
│   │   │   │   ├── shadow\_hand\_pen.yaml
│   │   │   │   ├── shadow\_hand\_push\_block.yaml
│   │   │   │   ├── shadow\_hand\_re\_orientation.yaml
│   │   │   │   ├── shadow\_hand\_scissors.yaml
│   │   │   │   ├── shadow\_hand\_swing\_cup.yaml
│   │   │   │   ├── shadow\_hand\_switch.yaml
│   │   │   │   ├── shadow\_hand\_test.yaml
│   │   │   │   ├── shadow\_hand\_two\_catch\_underarm.yaml
│   │   │   │   ├── shadow\_hand.yaml
│   │   │   │   ├── **td3**
│   │   │   │   │   ├── config.yaml
│   │   │   │   │   └── humanoid\_config.yaml
│   │   │   │   └── **trpo**
│   │   │   │       └── config.yaml
│   │   │   ├── **scripts**
│   │   │   │   └── **run\_experiments.sh**
│   │   │   ├── **tasks**
│   │   │   │   ├── **arm\_base**
│   │   │   │   │   ├── multiAgent.py
│   │   │   │   │   ├── oneFranka.py
│   │   │   │   │   └── vec\_task.py
│   │   │   │   ├── franka\_cabinet.py
│   │   │   │   ├── **hand\_base**
│   │   │   │   │   ├── base\_task.py
│   │   │   │   │   ├── \_\_init\_\_.py
│   │   │   │   │   ├── meta\_vec\_task.py
│   │   │   │   │   ├── multi\_task\_vec\_task.py
│   │   │   │   │   ├── multi\_vec\_task.py
│   │   │   │   │   └── vec\_task.py
│   │   │   │   ├── humanoid.py
│   │   │   │   ├── \_\_init\_\_.py
│   │   │   │   ├── shadow\_hand\_block\_stack.py
│   │   │   │   ├── shadow\_hand\_bottle\_cap.py
│   │   │   │   ├── shadow\_hand\_catch\_abreast.py
│   │   │   │   ├── shadow\_hand\_catch\_over2underarm.py
│   │   │   │   ├── shadow\_hand\_catch\_overarm.py
│   │   │   │   ├── shadow\_hand\_catch\_underarm.py
│   │   │   │   ├── shadow\_hand\_door\_close\_inward.py
│   │   │   │   ├── shadow\_hand\_door\_close\_outward.py
│   │   │   │   ├── shadow\_hand\_door\_open\_inward.py
│   │   │   │   ├── shadow\_hand\_door\_open\_outward.py
│   │   │   │   ├── shadow\_hand\_grasp\_and\_place.py
│   │   │   │   ├── shadow\_hand\_kettle.py
│   │   │   │   ├── shadow\_hand\_lift\_cup.py
│   │   │   │   ├── shadow\_hand\_lift\_overarm.py
│   │   │   │   ├── shadow\_hand\_lift.py
│   │   │   │   ├── shadow\_hand\_lift\_underarm2.py
│   │   │   │   ├── shadow\_hand\_lift\_underarm.py
│   │   │   │   ├── **shadow\_hand\_meta**
│   │   │   │   │   ├── \_\_init\_\_.py
│   │   │   │   │   ├── shadow\_hand\_meta\_ml1.py
│   │   │   │   │   ├── shadow\_hand\_meta\_ml1\_task\_info.py
│   │   │   │   │   ├── shadow\_hand\_meta\_mt1.py
│   │   │   │   │   ├── shadow\_hand\_meta\_mt1\_task\_info.py
│   │   │   │   │   ├── shadow\_hand\_meta\_mt20.py
│   │   │   │   │   ├── shadow\_hand\_meta\_mt20\_task\_info.py
│   │   │   │   │   ├── shadow\_hand\_meta\_mt5\_door.py
│   │   │   │   │   ├── shadow\_hand\_meta\_mt5.py
│   │   │   │   │   ├── shadow\_hand\_meta\_mt5\_task\_info.py
│   │   │   │   │   ├── shadow\_hand\_meta.py
│   │   │   │   │   └── shadow\_hand\_meta\_task\_info.py
│   │   │   │   ├── shadow\_hand\_meta.py
│   │   │   │   ├── shadow\_hand\_meta\_task\_info.py
│   │   │   │   ├── shadow\_hand\_over\_overarm.py
│   │   │   │   ├── shadow\_hand\_over.py
│   │   │   │   ├── shadow\_hand\_pen.py
│   │   │   │   ├── shadow\_hand\_push\_block.py
│   │   │   │   ├── shadow\_hand.py
│   │   │   │   ├── shadow\_hand\_re\_orientation.py
│   │   │   │   ├── shadow\_hand\_scissors.py
│   │   │   │   ├── shadow\_hand\_swing\_cup.py
│   │   │   │   ├── shadow\_hand\_switch.py
│   │   │   │   ├── shadow\_hand\_test.py
│   │   │   │   ├── shadow\_hand\_two\_catch\_abreast.py
│   │   │   │   └── shadow\_hand\_two\_catch\_underarm.py
│   │   │   ├── train.py
│   │   │   └── **utils**
│   │   │       ├── config.py
│   │   │       ├── contact\_buffer.py
│   │   │       ├── **logger**
│   │   │       │   ├── analysis.py
│   │   │       │   ├── plotter.py
│   │   │       │   └── tools.py
│   │   │       ├── parse\_task.py
│   │   │       ├── process\_marl.py
│   │   │       ├── process\_metarl.py
│   │   │       ├── process\_mtrl.py
│   │   │       ├── process\_sarl.py
│   │   │       ├── torch\_jit\_utils.py
│   │   │       └── util.py
│   │   ├── env\_wrappers.py
│   │   ├── **football**
│   │   │   ├── **encode**
│   │   │   │   ├── obs\_encode.py
│   │   │   │   └── rew\_encode.py
│   │   │   ├── **football\_env.py**
│   │   │   └── **multiagentenv.py**
│   │   ├── \_\_init\_\_.py
│   │   ├── **ma\_mujoco**
│   │   │   ├── \_\_init\_\_.py
│   │   │   └── **multiagent\_mujoco**
│   │   │       ├── **assets**
│   │   │       │   ├── coupled\_half\_cheetah.xml
│   │   │       │   ├── \_\_init\_\_.py
│   │   │       │   ├── manyagent\_ant\_\_stage1.xml
│   │   │       │   ├── manyagent\_ant.xml
│   │   │       │   ├── manyagent\_ant.xml.template
│   │   │       │   ├── manyagent\_swimmer\_\_bckp2.xml
│   │   │       │   ├── manyagent\_swimmer\_bckp.xml
│   │   │       │   └── manyagent\_swimmer.xml.template
│   │   │       ├── coupled\_half\_cheetah.py
│   │   │       ├── \_\_init\_\_.py
│   │   │       ├── manyagent\_ant.py
│   │   │       ├── manyagent\_swimmer.py
│   │   │       ├── **mujoco\_multi.py**
│   │   │       ├── **multiagentenv.py**
│   │   │       ├── obsk.py
│   │   │       └── **random\_mujoco\_multi.py**
│   │   ├── **mpe**
│   │   │   ├── core.py
│   │   │   ├── environment.py
│   │   │   ├── \_\_init\_\_.py
│   │   │   ├── MPE\_env.py
│   │   │   ├── multi\_discrete.py
│   │   │   ├── rendering.py
│   │   │   ├── scenario.py
│   │   │   └── **scenarios**
│   │   │       ├── \_\_init\_\_.py
│   │   │       ├── simple\_adversary.py
│   │   │       ├── simple\_attack.py
│   │   │       ├── simple\_crypto\_display.py
│   │   │       ├── simple\_crypto.py
│   │   │       ├── simple\_push.py
│   │   │       ├── simple\_reference.py
│   │   │       ├── simple\_speaker\_listener.py
│   │   │       ├── simple\_spread.py
│   │   │       ├── simple\_tag.py
│   │   │       └── simple\_world\_comm.py
│   │   └── **starcraft2**
│   │       ├── feature\_translation.py
│   │       ├── multiagentenv.py
│   │       ├── Random\_StarCraft2\_Env\_Multi.py
│   │       ├── Random\_StarCraft2\_Env.py
│   │       ├── smac\_maps.py
│   │       └── StarCraft2\_Env.py
│   ├── \_\_init\_\_.py
│   ├── **runner**
│   │   └── **shared**
│   │       ├── base\_runner.py
│   │       ├── football\_runner.py
│   │       ├── hands\_runner.py
│   │       ├── mpe\_runner.py
│   │       ├── mujoco\_runner.py
│   │       ├── smac\_multi\_runner.py
│   │       └── smac\_runner.py
│   ├── **scripts**
│   │   ├── \_\_init\_\_.py
│   │   ├── **train**
│   │   │   ├── \_\_init\_\_.py
│   │   │   ├── train\_football.py
│   │   │   ├── train\_hands.py
│   │   │   ├── train\_mpe.py
│   │   │   ├── train\_mujoco.py
│   │   │   ├── train\_smac\_multi.py
│   │   │   └── train\_smac.py
│   │   ├── train\_football.sh
│   │   ├── **train\_hands.sh**
│   │   ├── **train\_mpe.sh**
│   │   ├── **train\_mujoco.sh**
│   │   ├── train\_smac\_few\_shot.sh
│   │   ├── train\_smac\_multi.sh
│   │   └── train\_smac.sh
│   └── **utils**
│       ├── \_\_init\_\_.py
│       ├── shared\_buffer.py
│       ├── util.py
│       └── valuenorm.py
├── README.md
└── requirments.txt