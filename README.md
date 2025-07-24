# Geely E245 Software Register

This register applies to the Flyme Auto system deployed in the following car brands and models:

- Geely EX5
- Proton eMas 7
- Geely Galaxy E5

The purpose of this register is to serve as a centralized repository for understanding the evolution of the DHU and Flyme Auto software, as well as to keep track of release notes if they are made public.

Vehicle applications (such as Spotify, Energy, Phone, etc.) have their own versions. Based on user experience, it is possible for two cars to have the same Flyme Auto version installed but different versions of car applications. Tracking such variants of software bundles is more complex and is not included in this documentation repository.

The features or options tracked below are those of interest to most users.


| Version | Build    | Country    | Release Notes                       | Apple CarPlay | Android Auto | adb Access | CarbitLink while Driving | Selectable AVAS Sound |
| --------- | ---------- | ------------ | ------------------------------------- | --------------- | -------------- | ------------ | -------------------------- | ----------------------- |
| 1.1.0   |          | Australia  |                                     |               |              | Y          |                          | N                     |
|         |          | Malaysia   | Unknown                             | N¹           | N³          | Y          | Y                        | N                     |
|         |          | Costa Rica | Unknown                             | N¹           | N³          | Y          | Y                        | N                     |
| 1.1.2   | D513BF5F | Australia  |                                     |               |              |            |                          |                       |
| 1.1.3   | 60F75E77 | Costa Rica | Unknown                             | N¹           | N³          | N          | Y                        | N                     |
| 1.1.4   | 3B7B61D8 | Malaysia   | [Available](/Release-Notes/1.1.4_3B7B61D8_MYS.md) |               | N³          |            |                          | N                     |
| 1.1.5   |          | Australia  | [Available](/Release-Notes/1.1.5_AUS.md)          |               | N³          |            |                          | N                     |
|         | 9AFB221B | Malaysia   |                                     |               | N³          |            |                          | N                     |
|         | 24F4D77A | Costa Rica | Unknown                             | N⁴           | N³          | N          | N                        | N                     |
| 1.1.6   |          | Australia  |                                     | ?             | N³          |            |                          |                       |
|         | C0CC88A1 | Malaysia   | [Available](/Release-Notes/1.1.6_C0CC88A1_MYS.md) | Y             | N³          | N          | N                        | Y                     |
|         | 5F811B06 | Costa Rica | Unknown                             | Y             | N³          | N          | N                        | Y                     |
| 1.8.0.3 | FFF6979D | China      |                                     |               |              |            |                          |                       |

## Notes

¹ Not officially available but can be enabled through the engineering menu (aka secret menu) using the car's phone application.<br>
² Not officially available but can be enabled through the engineering menu (aka secret menu) using the car's phone application. However, once enabled, the setting will not persist after a system shutdown or reset.<br>
³ Not officially available yet, but can be enabled through adb and Headunit Reloaded.<br>
⁴ Some users got a build installed by the dealership with Apple CarPlay enabled by default<br>
? Mixed reports of users where the option is present for some and not for others.<br>

:warning: If you have [adb](https://developer.android.com/tools/adb) access and don't want to lose it, it is highly recommended to install [Geely EX5 Helper](https://eucalyptus-software-geely-ex5-mods.pages.dev/app-library?fbclid=IwY2xjawLt4rdleHRuA2FlbQIxMABicmlkETF5Zk9VaUhaMWljZ0wyTTI4AR4lZdZsNj7IQlUqDdamVBG2P3U6WChVTcrqTEsuYVpcr3UY5KDUiwF8V3x00g_aem_Ur9yQGfYOTxURHPlcOCHzg) before upgrading your car's software.
