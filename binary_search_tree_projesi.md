# Binary Search Tree Projesi

#### [7,5,1,8,3,6,0,9,4,2] dizisinin Binary-Search-Tree aşamalarını yazınız.

#### Root 7'dir.

#### 5 < 7 yani soluna ekledik.
| | |7|
|-|-|-|
| |/| |
|5| | |

#### 1 < 7 ve 1 < 5 olduğundan 5'in soluna ekledik.
| | | | |7|
|-|-|-|-|-|
| | | |/| |
| | |5| | |
| |/| | | |
|1| | | | |

#### 8 > 7 olduğundan 7'nin sağına ekledik.
|  |  |  |  |7 |  |  |
|- |- |- |- |- |- |- |
| | | |/| |\ | |
| | |5| | | |8|
| |/| | | | | |
|1| | | | | | |

#### 3 < 7 , 3 < 5 ve 3 > 1 olduğundan 1'in sağına ekledik.
|  |  |  |  |7 |  |  |
|- |- |- |- |- |- |- |
|  |  |  |/ |  |\ |  |
|  |  |5 |  |  |  |8 |
|  |/ |  |  |  |  |  |
|1 |  |  |  |  |  |  |
|  |\ |  |  |  |  |  |
|  |  |3 |  |  |  |  |

#### 6 < 7 ve 6 > 5 olduğundan 5'in sağına ekledik.
|  |  |  |  |7 |  |  |
|- |- |- |- |- |- |- |
|  |  |  |/ |  |\ |  |
|  |  |5 |  |  |  |8 |
|  |/ |  |\ |  |  |  |
|1 |  |  |  |6 |  |  |
|  |\ |  |  |  |  |  |
|  |  |3 |  |  |  |  |

#### 0 < 7 ve 0 < 5 ve 0 < 1 olduğundan 1'in soluna ekledik.
|  |  |  |  |  |  |7 |  |  |
|- |- |- |- |- |- |- |- |- |
|  |  |  |  |  |/ |  |\ |  |
|  |  |  |  |5 |  |  |  |8 |
|  |  |  |/ |  |\ |  |  |  |
|  |  |1 |  |  |  |6 |  |  |
|  |/ |  |\ |  |  |  |  |  |
|0 |  |  |  |3 |  |  |  |  |

#### 9 > 7 ve 9 > 8 olduğundan 8'in sağına ekledik.
|  |  |  |  |  |  |7 |  |  |  |  |
|- |- |- |- |- |- |- |- |- |- |- |
|  |  |  |  |  |/ |  |\ |  |  |  |
|  |  |  |  |5 |  |  |  |8 |  |  |
|  |  |  |/ |  |\ |  |  |  |\ |  |
|  |  |1 |  |  |  |6 |  |  |  |9 |
|  |/ |  |\ |  |  |  |  |  |  |  |
|0 |  |  |  |3 |  |  |  |  |  |  |

#### 4 < 7 ve 4 < 5 ve 4 > 1 ve 4 > 3 olduğundan 3'in sağına ekledik.
|  |  |  |  |  |  |7 |  |  |  |  |
|- |- |- |- |- |- |- |- |- |- |- |
|  |  |  |  |  |/ |  |\ |  |  |  |
|  |  |  |  |5 |  |  |  |8 |  |  |
|  |  |  |/ |  |\ |  |  |  |\ |  |
|  |  |1 |  |  |  |6 |  |  |  |9 |
|  |/ |  |\ |  |  |  |  |  |  |  |
|0 |  |  |  |3 |  |  |  |  |  |  |
|  |  |  |  |  |\ |  |  |  |  |  |
|  |  |  |  |  |  |4 |  |  |  |  |

#### 2 < 7 ve 2 < 5 ve 2 > 1 ve 2 < 3 olduğundan 3'in soluna ekledik.
|  |  |  |  |  |  |7 |  |  |  |  |
|- |- |- |- |- |- |- |- |- |- |- |
|  |  |  |  |  |/ |  |\ |  |  |  |
|  |  |  |  |5 |  |  |  |8 |  |  |
|  |  |  |/ |  |\ |  |  |  |\ |  |
|  |  |1 |  |  |  |6 |  |  |  |9 |
|  |/ |  |\ |  |  |  |  |  |  |  |
|0 |  |  |  |3 |  |  |  |  |  |  |
|  |  |  |/ |  |\ |  |  |  |  |  |
|  |  |2 |  |  |  |4 |  |  |  |  |

https://app.patika.dev/courses/veri-yapilari-ve-algoritmalar/binary-search-tree-proje
