Exception: NullReferenceException
Message:Object reference not set to an instance of an object.
Source:Eco.Gameplay

System.NullReferenceException: Object reference not set to an instance of an object.
   at Eco.Gameplay.Civics.CivicAction_ChangeElement.Description()
   at Eco.Gameplay.Civics.Elections.Election.Description()
   at lambda_method15309(Closure , IMvcNetClient , Object )
   at Eco.Core.Controller.SyncMethodInfo.GetValue(IMvcNetClient client, Object obj)
   at Eco.Core.Controller.ControllerManager.PackageMember(IMvcNetClient boundClient, IController controller, ISyncMemberInfo memberInfo)
Outer Exceptions:
Error during packaging property 'Registrars' of 'Eco.Gameplay.Systems.GlobalData'
Error during packaging property 'IdToObj' of 'Eco.Core.Systems.Registrar`1[[Eco.Gameplay.Civics.Elections.Election, Eco.Gameplay, Version=1.0.0.0, Culture=neutral, PublicKeyToken=null]]'
Error during packaging property 'Description' of 'Eco.Gameplay.Civics.Elections.Election'