# ha_MIscale
小米体脂秤v1/V2数据在HA无法很好地按人来录入体重和体脂的数据，尤其家庭成员中体重有相近的人，出现误判几率很高。
本贴在Nodered通过流让体重和体质数据以手机弹窗提示的形式，给人选中该体重和体脂数据属于哪位家庭的成员， 然后，体重和体脂数据就会录入对应家庭人员的sensor。
这里需要提前准备
1. 手机安装HA的APP，并在HA里面找到对应的移动设备的实体
2. 开通通知功能，让手机可以接收HA的信息。
3. 称重的时候， 需要打开手机的HA的APP。
4. 秤设备已经接入HA能接收秤的数据。推荐用Passive BLE Monitor来让秤接入HA。
