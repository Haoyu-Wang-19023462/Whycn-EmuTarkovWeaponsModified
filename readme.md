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
|5bbde41ed4351e003562b038|pistolgrip_mosin_tacfire_pgmn                |-50% Recoil��+50 Ergonomics                                                                                                 |
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

> Find Github Repository��https://github.com/Haoyu-Wang-19023462/Whycn-EmuTarkovWeaponsModified ��Update, download at [releases](https://github.com/Haoyu-Wang-19023462/Whycn-EmuTarkovWeaponsModified/releases), unzip the zip package into a folder with has the same name with the file.





# Why-cn���������߰��������Ʒ�����MOD

#### �汾 0.0.1

&nbsp;&nbsp;������ٷ���ΪһЩ����ƽ���ԭ��������һЩ����İ�װ������˵CQRǰ�հ�����ʵ���ǿ��԰�װ��4Ӣ�絼���ϣ���AKǹ���ǿ��԰�װCQR�հѵġ�����RK-2ǰ�հ������Ȱ汾�ǲ��ή���˻���Ч�ġ���MOD���������հѽ�����΢����  

&nbsp;&nbsp;��MOD������ȥ�ƻ�ǹе��������ĺ����ԡ�֮ǰ������һЩMOD���Ѻ�ɫ�߼������װ�ڸ����17�ϣ���װһ��20Ӣ��ARǹ�ܡ���������Ҳ̫��Ϸ�ˡ����Ҳ�����ǹ�ͳ�����Ҫ����һ����9mm�ھ�ħ��ѹ����5.56mm�ھ����������ס����������ڸ��ĵĻ����Ͼ������������ԣ�����9x19�ĸ����17���԰�װͬ��9x19��MPX����������7.62x54��SVDS���԰�װͬ��7.62x54��Ī��ǹ��ת��������������һЩ������԰�װ����ľ������ˣ���ʵ��һ���ȸо���������MP9��PP-19���԰�װ����˵�
50�����ģ�SR25���԰�װSA58��30����ϻ��50�����ĵȵȡ�  

&nbsp;&nbsp;�����ط���һЩ��ֵ�ĸ��ģ����罫APB��ǹ������Ч����ǿ�ܸߣ�Ī�����ʽ����ǹʽ�հѵ�����Ч�����˻���Ч��ǿ�ܸߣ������˸����17��SR25��ȫ�Զ�ģʽ������Ϊ�����������ܹ�ʹ�õĳ����������Ϳ�������ˢ���ǵ�����ר���ȼ���������ǿ��֢�޸ģ���  
&nbsp;&nbsp;���������޸ģ������ӵ��һ�ѿ��ƻ���ǿ��9x19mm����˳��ǹ�����ȸо�����9x18mmAPB���ǹ��SR25 7.62x51mmͻ����ǹ�ȡ�  

&nbsp;&nbsp;���ڸ�M700����12.7x108mm���ӵ����䣬����ȫ����Ϊ�˺��棬���ӵ���ʱ��ϲ�б����ȷʵ���͡�  

��MOD��0.12.7.8642�ٷ����ݿ���Ķ�����  
����������������Ʒ��ǹе��MOD��ͻ��������Ч�볢��ж������MOD��������档  

**��װ**

1. ���Ƚ����ļ��з���server\user\mods�ļ����¡����û��mods�ļ��У��½�һ��Ȼ��Ž�ȥ��

2. �����¼�����ӵ����server\user\configs�ļ����µ�mods.json�ļ��С�  
(����������ı��༭��������ļ�����Ҫ����"```javascript" �� "```" ���С�)
```javascript
{
	"name": "EmuTarkovWeaponsModified",
	"author": "Whycn",
	"version": "0.0.1",
	"enabled": true
}
```

**ж��**

���Ű�װ���跴�����������ת��

**�����ĸ������£�**

|��ƷID                  |��Ʒ�����ֶ�                                 |��Ʒ                     |��������                                                                                           | 
|------------------------|---------------------------------------------|-------------------------|---------------------------------------------------------------------------------------------------|
|5a17fb9dfcdbcbcae6687291|stock_aps_toz_apb_wire                       |APBǹ��                  |-80%������                                                                                         |
|5a78948ec5856700177b1124|mount_870_xs_shot_rail_ghost_ring            |M870������             |�ɰ�װPP91 Rotor 43 RIS����                                                                        |
|5abccb7dd8ce87001773e277|weapon_toz_apb_9x18pm                        |APB�����Զ���ǹ          |�ɰ�װPM/PPSH 84�����ġ�׼�ǿɰ�װM870�����졢���ſɰ�װTT01���ŵ���                             |
|5649d9a14bdc2d79388b4580|sight_rear_ak_tactica_tula_tt01              |TT01���ŵ���             |�ɰ�װDLOC-IRD֧��                                                                                 |
|5a7dbfc1159bd40016548fde|foregrip_all_hera_arms_cqr_grip              |CQR�հ�                  |ȥ����ԭ������������                                                                               |
|5d3eb59ea4b9361c284bb4b2|barrel_57_fn_120mm_threaded_57x28            |FN57����ǹ��             |�ɰ�װP90����������                                                                                |
|5d67abc1a4b93614ec50137f|weapon_fn_five_seven_57x28_fde               |FN P90 FDE PDR           |�ɰ�װ�����17 ZT Spartan+��ϻ                                                                     |
|5a6b5ed88dc32e000c52ec86|barrel_glock_salient_arms_114mm_threaded_9x19|�����17 SAI+����ǹ��    |�ɰ�װTACCOM MPX������                                                                             |
|5a7ad55551dfba0015068f42|mount_glock_aimtech_tiger_shark_glock        |�����Tiger Shark����    |�ɰ�װDLOC-IRD֧��                                                                                 |
|5a7ae0c351dfba0017554310|weapon_glock_glock_17_gen3_9x19              |�����17��ǹ             |����ȫ�Զ�850��ÿ��ģʽ���ɰ�װSR1MP�Ĺ�                                                           |
|5a7b4900e899ef197b331a2a|mount_glock_um_tactical_um3_sight_mount      |UM3����                  |�ɰ�װDLOC-IRD֧��                                                                                 |
|5a71e4f48dc32e001207fb26|reciever_glock_zev_tech_spartan_rmr_cut_gen_3|�����17 ZT Spartan+��ϻ |�ɰ�װDLOC-IRD֧��                                                                                 |
|5bfea6e90db834001b7347f3|weapon_remington_model_700_762x51            |M700˨��ʽ�ѻ�ǹ         |�ɷ���12.7x108mm���ֵ�ҩ                                                                           |
|5cde7afdd7f00c000d36b89d|handguard_m700_abarms_mrs_mod_x_gen_3        |M700 MOD X Gen.3��ľ     |�ɰ�װMPR45���õ���                                                                                |
|5d25a6a48abbc306c62e6310|mag_m700_mdt_aics_762x51_12                  |M700 MDT AICS 12����ϻ   |�ɰ�װ12.7x108mm���ֵ�ҩ                                                                           |
|5bae13ded4351e44f824bf38|mag_mosin_promag_opfor_mag_762x54_10         |Ī��ProMag OPFOR 10����ϻ|ȥ������������                                                                                     |
|5bbde41ed4351e003562b038|pistolgrip_mosin_tacfire_pgmn                |Ī��PGMN��ǹʽ�հ�       |-50%��������+50�˻���Ч                                                                            |
|5bfd4cd60db834001c38f095|barrel...mosin_custom_threaded_sawn_off_220mm|Ī�����ʽ220mmǹ��      |�ɰ�װĪ��Witt������                                                                               |
|5de8f237bbaf010b10528a70|muzzle_mp9_bt_supressor_mount_9x19           |MP9����������            |�ɰ�װTACCOM MPX������                                                                             |
|5e00903ae9dc277128008b87|weapon_bt_mp9_9x19                           |MP9΢�ͳ��ǹ            |�ɰ�װ�����SGMT 50�����ġ�MPX ULSSǹ��                                                            |
|5cc70093e4a949033c734312|mag_p90_fn_p90_std_57x28_50                  |P90 50����ϻ             |װж�ٶ�����0                                                                                      |
|57ee59b42459771c7b045da5|mount_pp-91_rotor_43_kedr_ris                |PP91 Rotor 43 RIS����    |�ɰ�װSR1MP�Ĺ�                                                                                    |
|57f4c844245977379d5c14d1|weapon_zmz_pp-9_9x18pmm                      |PP-9 Klin΢�ͳ��ǹ      |�ɰ�װRK-3��ǹʽ�հѡ��ɰ�װPM/PPSH 84������                                                       |
|59984ab886f7743e98271174|weapon_izhmash_pp-19-01_9x19                 |PP-19-01���ǹ           |�ɰ�װ�����SGMT 50�����ġ��ɰ�װTACCOM MPX������                                                  |
|5a27bad7c4a282000b15184b|mount_sr1mp_tochmash_std_4_rail              |SR1MP�Ĺ�                |�ɰ�װRK-2ǰ�հѡ��ɰ�װDLOC-IRD֧��                                                               |
|5df8ce05b11454561e39243b|weapon_kac_sr25_762x51                       |SR25 DMR                 |����ȫ�Զ�700��ÿ��ģʽ���ɰ�װM1A X-14 50�����ġ��ɰ�װSA58 X-FAL 50�����ġ��ɰ�װSA58Ӣ��30����ϻ|
|5c471bfc2e221602b21d4e17|muzzle_svd_izhmash_svd_s_std_762x54          |SVDS 22��ǹ��������      |�ɰ�װĪ��TR+ǹ��ת�������ɰ�װĪ��Witt������                                                      |
|59e6687d86f77411d949b251|weapon_molot_akm_vpo_209_366_TKM             |VPO-209 ���Զ�����ǹ     |����ȫ�Զ�600��ÿ��ģʽ��ȫ����ֵ��AKMNԭ����ֵ�ӻ�8.3%�����趨                                    |
|5c1bc5af2e221602b412949b|foregrip_all_zenit_rk_2                      |RK-2��ֱǰ�հ�           |-0�˻���Ч                                                                                         |

**����**

0.12.7.8642����ͨ��  
��Ereshkigal-AllExaminedItemsPlusNoItemsWeightPlusIncreasedAmmoStacksSize-1.0.0����  
��Frumorn-AutoSaiga12-1.0.0����  

> ��Ŀ��ַ��https://github.com/Haoyu-Wang-19023462/Whycn-EmuTarkovWeaponsModified ����Ŀ���¡���������[releases](https://github.com/Haoyu-Wang-19023462/Whycn-EmuTarkovWeaponsModified/releases)�����أ���ѹ������ѹ�����ļ�����ͬ���ļ����С�