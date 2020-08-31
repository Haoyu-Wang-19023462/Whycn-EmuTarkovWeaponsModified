# Why-cn's self-use EmuTarkov Weapon Mod

#### Version 0.0.1

The data was modified based on the official EmuTarkov 0.12.7.8642's database.  
This mod might conflict with other mods which change items and firearms!  
If it doesn't take any effect, please try to uninstall other mods or clear the cache.  

**Installation**

1. Add this folder in server\user\mods

2. Add these lines to your mods.json in Server\user\configs  
(If you are using this readme file in notepad, don't copy "```javascript" and "```" lines.)
```javascript
{
	"name": "EmuTarkovWeaponsModified",
	"author": "Whycn",
	"version": "0.0.1",
	"enabled": true
}
```

**Uninstallation**

Please reverse the steps above.

**Changes:**

|Item ID                 |Name                                         |Changes                                                                                                                     |
|------------------------|---------------------------------------------|----------------------------------------------------------------------------------------------------------------------------|
|5a17fb9dfcdbcbcae6687291|stock_aps_toz_apb_wire                       |-80% Recoil                                                                                                                 |
|5a78948ec5856700177b1124|mount_870_xs_shot_rail_ghost_ring            |Can be adapted to "PP91 Rotor 43 RIS"                                                                                       |
|5abccb7dd8ce87001773e277|weapon_toz_apb_9x18pm                        |Can be adapted to "PM/PPSH 84 Rounds", front sight can be adapted to "M870 Ghost Ring", Rear sight  can be adapted to "TT01"|
|5649d9a14bdc2d79388b4580|sight_rear_ak_tactica_tula_tt01              |Can be adapted to "DLOC-IRD"                                                                                                |
|5a7dbfc1159bd40016548fde|foregrip_all_hera_arms_cqr_grip              |Removed incompatibility restrictions                                                                                        |
|5d3eb59ea4b9361c284bb4b2|barrel_57_fn_120mm_threaded_57x28            |Can be adapted to "P90 flash hider"                                                                                         |
|5d67abc1a4b93614ec50137f|weapon_fn_five_seven_57x28_fde               |Can be adapted to "Glock 17 ZT Spartan+ Slide"                                                                              |
|5a6b5ed88dc32e000c52ec86|barrel_glock_salient_arms_114mm_threaded_9x19|Can be adapted to "TACCOM MPX brake"                                                                                        |
|5a7ad55551dfba0015068f42|mount_glock_aimtech_tiger_shark_glock        |Can be adapted to "DLOC-IRD"                                                                                                |
|5a7ae0c351dfba0017554310|weapon_glock_glock_17_gen3_9x19              |Add fullauto 850 RPM mode, Can be adapted to "SR1MP 4 rails"                                                                |
|5a7b4900e899ef197b331a2a|mount_glock_um_tactical_um3_sight_mount      |Can be adapted to "DLOC-IRD"                                                                                                |
|5a71e4f48dc32e001207fb26|reciever_glock_zev_tech_spartan_rmr_cut_gen_3|Can be adapted to "DLOC-IRD"                                                                                                |
|5bfea6e90db834001b7347f3|weapon_remington_model_700_762x51            |Can fire 2 kinds of 12.7x108mm bullets                                                                                      |
|5cde7afdd7f00c000d36b89d|handguard_m700_abarms_mrs_mod_x_gen_3        |Can be adapted to "MPR45 backup rail                                                                                        |
|5d25a6a48abbc306c62e6310|mag_m700_mdt_aics_762x51_12                  |Can be adapted to 2 kinds of 12.7x108mm bullets                                                                             |
|5bae13ded4351e44f824bf38|mag_mosin_promag_opfor_mag_762x54_10         |Removed incompatibility restrictions                                                                                        |
|5bbde41ed4351e003562b038|pistolgrip_mosin_tacfire_pgmn                |-50% Recoil，+50 Ergonomics                                                                                                 |
|5bfd4cd60db834001c38f095|barrel...mosin_custom_threaded_sawn_off_220mm|Can be adapted to "Mosin Witt brake"                                                                                        |
|5de8f237bbaf010b10528a70|muzzle_mp9_bt_supressor_mount_9x19           |Can be adapted to "TACCOM MPX brake"                                                                                        |
|5e00903ae9dc277128008b87|weapon_bt_mp9_9x19                           |Can be adapted to "Glock SGMT 50 Rounds", "MPX ULSS Stock"                                                                  |
|5cc70093e4a949033c734312|mag_p90_fn_p90_std_57x28_50                  |LoadUnloadModifier 0                                                                                                        |
|57ee59b42459771c7b045da5|mount_pp-91_rotor_43_kedr_ris                |Can be adapted to "SR1MP 4 rails"                                                                                           |
|57f4c844245977379d5c14d1|weapon_zmz_pp-9_9x18pmm                      |Can be adapted to "RK-3 pistol grip", "PM/PPSH 84 Rounds"                                                                   |
|59984ab886f7743e98271174|weapon_izhmash_pp-19-01_9x19                 |Can be adapted to "Glock SGMT 50 rounds", "TACCOM MPX brake"                                                                |
|5a27bad7c4a282000b15184b|mount_sr1mp_tochmash_std_4_rail              |Can be adapted to "RK-2 fore grip", "DLOC-IRD"                                                                              |
|5df8ce05b11454561e39243b|weapon_kac_sr25_762x51                       |Add fullauto 700 RPM mode, Can be adapted to "M1A X-14 50 rounds", "SA58 X-FAL 50 rounds", "SA58 British 30 rounds"         |
|5c471bfc2e221602b21d4e17|muzzle_svd_izhmash_svd_s_std_762x54          |Can be adapted to "Mosin TR+ Muzzle adapter", "Mpsin Witt brake"                                                            |
|59e6687d86f77411d949b251|weapon_molot_akm_vpo_209_366_TKM             |Add fullauto 600 RPM mode, All values are reset according to 8.3% deterioration of the original AKMN value                  |
|5c1bc5af2e221602b412949b|foregrip_all_zenit_rk_2                      |-0 Ergonomics                                                                                                               |

**Tests**

0.12.7.8642 passed.  
Compatible with "Ereshkigal-AllExaminedItemsPlusNoItemsWeightPlusIncreasedAmmoStacksSize-1.0.0"  
Compatible with "Frumorn-AutoSaiga12-1.0.0"  

> Find Github Repository：https://github.com/Haoyu-Wang-19023462/Whycn-EmuTarkovWeaponsModified ，Update, download at [releases](https://github.com/Haoyu-Wang-19023462/Whycn-EmuTarkovWeaponsModified/releases), unzip the zip package into a folder with has the same name with the file.





# Why-cn的自用离线版逃离塔科夫武器MOD

#### 版本 0.0.1

&nbsp;&nbsp;尼基塔官方因为一些诸如平衡的原因限制了一些组件的安装。比如说CQR前握把在现实中是可以安装到4英寸导轨上，且AK枪族是可以安装CQR握把的。又如RK-2前握把在早先版本是不会降低人机功效的。本MOD将这两个握把进行了微调。  

&nbsp;&nbsp;本MOD尽量不去破坏枪械附件搭配的合理性。之前看见过一些MOD，把红色高级缓冲管装在格洛克17上，再装一个20英寸AR枪管……这尼玛也太出戏了……且不论手枪掏出来跟要击剑一样，9mm口径魔法压缩成5.56mm口径就尼玛离谱……所以我在更改的基础上尽量保留合理性，比如9x19的格洛克17可以安装同样9x19的MPX的制退器；7.62x54的SVDS可以安装同样7.62x54的莫辛枪口转接器和制退器；一些导轨可以安装更多的镜（懒了，其实就一个热感镜……）；MP9和PP-19可以安装格洛克的
50发弹鼓，SR25可以安装SA58的30发弹匣和50发弹鼓等等。  

&nbsp;&nbsp;其他地方如一些数值的更改，比如将APB的枪托制退效果加强很高，莫辛锯短式的手枪式握把的制退效果和人机功效增强很高，增加了格洛克17、SR25的全自动模式，均是为了增加他们能够使用的场景，这样就可以用来刷他们的武器专精等级啦（面向强迫症修改）。  
&nbsp;&nbsp;配合上面的修改，你可以拥有一把客制化很强的9x19mm格洛克冲锋枪（带热感镜），9x18mmAPB冲锋枪，SR25 7.62x51mm突击步枪等。  

&nbsp;&nbsp;至于给M700加入12.7x108mm的子弹适配，这完全就是为了好玩，上子弹的时候喜感爆棚。但确实很猛。  

本MOD由0.12.7.8642官方数据库更改而来。  
可能与其他更改物品、枪械的MOD冲突！若不生效请尝试卸载其他MOD或清除缓存。  

**安装**

1. 首先将本文件夹放在server\user\mods文件夹下。如果没有mods文件夹，新建一个然后放进去。

2. 将以下几行添加到你的server\user\configs文件夹下的mods.json文件中。  
(如果你是用文本编辑器看这个文件，不要复制"```javascript" 和 "```" 两行。)
```javascript
{
	"name": "EmuTarkovWeaponsModified",
	"author": "Whycn",
	"version": "0.0.1",
	"enabled": true
}
```

**卸载**

按着安装步骤反向操作。！了转反

**作出的更改如下：**

|物品ID                  |物品名称字段                                 |物品                     |更改内容                                                                                           | 
|------------------------|---------------------------------------------|-------------------------|---------------------------------------------------------------------------------------------------|
|5a17fb9dfcdbcbcae6687291|stock_aps_toz_apb_wire                       |APB枪托                  |-80%后坐力                                                                                         |
|5a78948ec5856700177b1124|mount_870_xs_shot_rail_ghost_ring            |M870鬼环导轨             |可安装PP91 Rotor 43 RIS导轨                                                                        |
|5abccb7dd8ce87001773e277|weapon_toz_apb_9x18pm                        |APB消音自动手枪          |可安装PM/PPSH 84发弹鼓、准星可安装M870鬼环导轨、照门可安装TT01照门导轨                             |
|5649d9a14bdc2d79388b4580|sight_rear_ak_tactica_tula_tt01              |TT01照门导轨             |可安装DLOC-IRD支架                                                                                 |
|5a7dbfc1159bd40016548fde|foregrip_all_hera_arms_cqr_grip              |CQR握把                  |去除了原生不兼容限制                                                                               |
|5d3eb59ea4b9361c284bb4b2|barrel_57_fn_120mm_threaded_57x28            |FN57螺纹枪管             |可安装P90闪光抑制器                                                                                |
|5d67abc1a4b93614ec50137f|weapon_fn_five_seven_57x28_fde               |FN P90 FDE PDR           |可安装格洛克17 ZT Spartan+机匣                                                                     |
|5a6b5ed88dc32e000c52ec86|barrel_glock_salient_arms_114mm_threaded_9x19|格洛克17 SAI+螺纹枪管    |可安装TACCOM MPX制退器                                                                             |
|5a7ad55551dfba0015068f42|mount_glock_aimtech_tiger_shark_glock        |格洛克Tiger Shark导轨    |可安装DLOC-IRD支架                                                                                 |
|5a7ae0c351dfba0017554310|weapon_glock_glock_17_gen3_9x19              |格洛克17手枪             |增加全自动850发每分模式、可安装SR1MP四轨                                                           |
|5a7b4900e899ef197b331a2a|mount_glock_um_tactical_um3_sight_mount      |UM3导轨                  |可安装DLOC-IRD支架                                                                                 |
|5a71e4f48dc32e001207fb26|reciever_glock_zev_tech_spartan_rmr_cut_gen_3|格洛克17 ZT Spartan+机匣 |可安装DLOC-IRD支架                                                                                 |
|5bfea6e90db834001b7347f3|weapon_remington_model_700_762x51            |M700栓动式狙击枪         |可发射12.7x108mm两种弹药                                                                           |
|5cde7afdd7f00c000d36b89d|handguard_m700_abarms_mrs_mod_x_gen_3        |M700 MOD X Gen.3护木     |可安装MPR45备用导轨                                                                                |
|5d25a6a48abbc306c62e6310|mag_m700_mdt_aics_762x51_12                  |M700 MDT AICS 12发弹匣   |可安装12.7x108mm两种弹药                                                                           |
|5bae13ded4351e44f824bf38|mag_mosin_promag_opfor_mag_762x54_10         |莫辛ProMag OPFOR 10发弹匣|去除不兼容限制                                                                                     |
|5bbde41ed4351e003562b038|pistolgrip_mosin_tacfire_pgmn                |莫辛PGMN手枪式握把       |-50%后坐力，+50人机功效                                                                            |
|5bfd4cd60db834001c38f095|barrel...mosin_custom_threaded_sawn_off_220mm|莫辛锯短式220mm枪管      |可安装莫辛Witt制退器                                                                               |
|5de8f237bbaf010b10528a70|muzzle_mp9_bt_supressor_mount_9x19           |MP9消音器基座            |可安装TACCOM MPX制退器                                                                             |
|5e00903ae9dc277128008b87|weapon_bt_mp9_9x19                           |MP9微型冲锋枪            |可安装格洛克SGMT 50发弹鼓、MPX ULSS枪托                                                            |
|5cc70093e4a949033c734312|mag_p90_fn_p90_std_57x28_50                  |P90 50发弹匣             |装卸速度修正0                                                                                      |
|57ee59b42459771c7b045da5|mount_pp-91_rotor_43_kedr_ris                |PP91 Rotor 43 RIS导轨    |可安装SR1MP四轨                                                                                    |
|57f4c844245977379d5c14d1|weapon_zmz_pp-9_9x18pmm                      |PP-9 Klin微型冲锋枪      |可安装RK-3手枪式握把、可安装PM/PPSH 84发弹鼓                                                       |
|59984ab886f7743e98271174|weapon_izhmash_pp-19-01_9x19                 |PP-19-01冲锋枪           |可安装格洛克SGMT 50发弹鼓、可安装TACCOM MPX制退器                                                  |
|5a27bad7c4a282000b15184b|mount_sr1mp_tochmash_std_4_rail              |SR1MP四轨                |可安装RK-2前握把、可安装DLOC-IRD支架                                                               |
|5df8ce05b11454561e39243b|weapon_kac_sr25_762x51                       |SR25 DMR                 |增加全自动700发每分模式、可安装M1A X-14 50发弹鼓、可安装SA58 X-FAL 50发弹鼓、可安装SA58英制30发弹匣|
|5c471bfc2e221602b21d4e17|muzzle_svd_izhmash_svd_s_std_762x54          |SVDS 22寸枪管制退器      |可安装莫辛TR+枪口转接器、可安装莫辛Witt制退器                                                      |
|59e6687d86f77411d949b251|weapon_molot_akm_vpo_209_366_TKM             |VPO-209 半自动霰弹枪     |增加全自动600发每分模式、全部数值按AKMN原厂数值劣化8.3%重新设定                                    |
|5c1bc5af2e221602b412949b|foregrip_all_zenit_rk_2                      |RK-2垂直前握把           |-0人机功效                                                                                         |

**测试**

0.12.7.8642测试通过  
与Ereshkigal-AllExaminedItemsPlusNoItemsWeightPlusIncreasedAmmoStacksSize-1.0.0兼容  
与Frumorn-AutoSaiga12-1.0.0兼容  

> 项目地址：https://github.com/Haoyu-Wang-19023462/Whycn-EmuTarkovWeaponsModified ，项目更新、下载请在[releases](https://github.com/Haoyu-Wang-19023462/Whycn-EmuTarkovWeaponsModified/releases)中下载，将压缩包解压到与文件名相同的文件夹中。