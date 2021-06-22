在怪物的腳本Update()裡
用GameObject.Find("").transform.position得到玩家的位置
如果玩家的x位置<怪物的x位置,就用rigidbody2D的AddForce讓怪物移動位置
AddFoce的使用方式 AddForce(new Vector()),ForceMode2D.施力方式)
像是
this.gameObject.transform.position+=new Vector3(5,0,0);

