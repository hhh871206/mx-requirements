# 权限管理

## 需求

### 权限设置
* 可以用角色来设置一组权限
* 1个帐号可以设置1个或者多个角色
   * 角色的权限如果更新，则角色组内帐号也同步更新
* 1个帐号可以单独设置权限
* 在设置角色后，依然可以单独设置权限
   * 如果增加角色包含权限之外的权限，则保持原来的角色
   * 如果取消了某些角色包含的权限，则需要取消当前角色，并且从角色组中移除当前用户
