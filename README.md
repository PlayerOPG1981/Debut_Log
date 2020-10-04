Error in patch.Apply(): System.Xml.XPath.XPathException: '/Defs/ThingCategoryDef[defName="SurvivalTools"' has an invalid token.
  at MS.Internal.Xml.XPath.XPathParser.CheckToken (MS.Internal.Xml.XPath.XPathScanner+LexKind t) [0x00023] in <1d98d70bb7d8453b80c25aa561fdecd1>:0 
  at MS.Internal.Xml.XPath.XPathParser.PassToken (MS.Internal.Xml.XPath.XPathScanner+LexKind t) [0x00000] in <1d98d70bb7d8453b80c25aa561fdecd1>:0 
  at MS.Internal.Xml.XPath.XPathParser.ParsePredicate (MS.Internal.Xml.XPath.AstNode qyInput) [0x0001b] in <1d98d70bb7d8453b80c25aa561fdecd1>:0 
  at MS.Internal.Xml.XPath.XPathParser.ParseStep (MS.Internal.Xml.XPath.AstNode qyInput) [0x0008f] in <1d98d70bb7d8453b80c25aa561fdecd1>:0 
  at MS.Internal.Xml.XPath.XPathParser.ParseRelativeLocationPath (MS.Internal.Xml.XPath.AstNode qyInput) [0x00002] in <1d98d70bb7d8453b80c25aa561fdecd1>:0 
  at MS.Internal.Xml.XPath.XPathParser.ParseLocationPath (MS.Internal.Xml.XPath.AstNode qyInput) [0x0002d] in <1d98d70bb7d8453b80c25aa561fdecd1>:0 
  at MS.Internal.Xml.XPath.XPathParser.ParsePathExpr (MS.Internal.Xml.XPath.AstNode qyInput) [0x00059] in <1d98d70bb7d8453b80c25aa561fdecd1>:0 
  at MS.Internal.Xml.XPath.XPathParser.ParseUnionExpr (MS.Internal.Xml.XPath.AstNode qyInput) [0x00000] in <1d98d70bb7d8453b80c25aa561fdecd1>:0 
  at MS.Internal.Xml.XPath.XPathParser.ParseUnaryExpr (MS.Internal.Xml.XPath.AstNode qyInput) [0x0003e] in <1d98d70bb7d8453b80c25aa561fdecd1>:0 
  at MS.Internal.Xml.XPath.XPathParser.ParseMultiplicativeExpr (MS.Internal.Xml.XPath.AstNode qyInput) [0x00000] in <1d98d70bb7d8453b80c25aa561fdecd1>:0 
  at MS.Internal.Xml.XPath.XPathParser.ParseAdditiveExpr (MS.Internal.Xml.XPath.AstNode qyInput) [0x00000] in <1d98d70bb7d8453b80c25aa561fdecd1>:0 
  at MS.Internal.Xml.XPath.XPathParser.ParseRelationalExpr (MS.Internal.Xml.XPath.AstNode qyInput) [0x00000] in <1d98d70bb7d8453b80c25aa561fdecd1>:0 
  at MS.Internal.Xml.XPath.XPathParser.ParseEqualityExpr (MS.Internal.Xml.XPath.AstNode qyInput) [0x00000] in <1d98d70bb7d8453b80c25aa561fdecd1>:0 
  at MS.Internal.Xml.XPath.XPathParser.ParseAndExpr (MS.Internal.Xml.XPath.AstNode qyInput) [0x00000] in <1d98d70bb7d8453b80c25aa561fdecd1>:0 
  at MS.Internal.Xml.XPath.XPathParser.ParseOrExpr (MS.Internal.Xml.XPath.AstNode qyInput) [0x00000] in <1d98d70bb7d8453b80c25aa561fdecd1>:0 
  at MS.Internal.Xml.XPath.XPathParser.ParseExpresion (MS.Internal.Xml.XPath.AstNode qyInput) [0x00023] in <1d98d70bb7d8453b80c25aa561fdecd1>:0 
  at MS.Internal.Xml.XPath.XPathParser.ParseXPathExpresion (System.String xpathExpresion) [0x0000d] in <1d98d70bb7d8453b80c25aa561fdecd1>:0 
  at MS.Internal.Xml.XPath.QueryBuilder.Build (System.String query, System.Boolean allowVar, System.Boolean allowKey) [0x00015] in <1d98d70bb7d8453b80c25aa561fdecd1>:0 
  at MS.Internal.Xml.XPath.QueryBuilder.Build (System.String query, System.Boolean& needContext) [0x00000] in <1d98d70bb7d8453b80c25aa561fdecd1>:0 
  at System.Xml.XPath.XPathExpression.Compile (System.String xpath, System.Xml.IXmlNamespaceResolver nsResolver) [0x00005] in <1d98d70bb7d8453b80c25aa561fdecd1>:0 
  at System.Xml.XPath.XPathExpression.Compile (System.String xpath) [0x00000] in <1d98d70bb7d8453b80c25aa561fdecd1>:0 
  at System.Xml.XPath.XPathNavigator.Select (System.String xpath) [0x00000] in <1d98d70bb7d8453b80c25aa561fdecd1>:0 
  at System.Xml.XmlNode.SelectNodes (System.String xpath) [0x0000c] in <1d98d70bb7d8453b80c25aa561fdecd1>:0 
  at System.Xml.XmlNode.SelectSingleNode (System.String xpath) [0x00000] in <1d98d70bb7d8453b80c25aa561fdecd1>:0 
  at Verse.PatchOperationConditional.ApplyWorker (System.Xml.XmlDocument xml) [0x00000] in <96ea46bebfdc4f6fb53ea63e897d1cc5>:0 
  at Verse.PatchOperation.Apply (System.Xml.XmlDocument xml) [0x00023] in <96ea46bebfdc4f6fb53ea63e897d1cc5>:0 
  at Verse.PatchOperationSequence.ApplyWorker (System.Xml.XmlDocument xml) [0x00016] in <96ea46bebfdc4f6fb53ea63e897d1cc5>:0 
  at Verse.PatchOperation.Apply (System.Xml.XmlDocument xml) [0x00023] in <96ea46bebfdc4f6fb53ea63e897d1cc5>:0 
  at Verse.PatchOperationFindMod.ApplyWorker (System.Xml.XmlDocument xml) [0x0003a] in <96ea46bebfdc4f6fb53ea63e897d1cc5>:0 
  at Verse.PatchOperation.Apply (System.Xml.XmlDocument xml) [0x00023] in <96ea46bebfdc4f6fb53ea63e897d1cc5>:0 
  at Verse.LoadedModManager.ApplyPatches (System.Xml.XmlDocument xmlDoc, System.Collections.Generic.Dictionary`2[TKey,TValue] assetlookup) [0x00038] in <96ea46bebfdc4f6fb53ea63e897d1cc5>:0 
Verse.Log:Error(String, Boolean)
Verse.LoadedModManager:ApplyPatches(XmlDocument, Dictionary`2)
Verse.LoadedModManager:LoadAllActiveMods()
Verse.PlayDataLoader:DoPlayLoad()
Verse.PlayDataLoader:LoadAllPlayData(Boolean)
Verse.<>c:<Start>b__6_1()
Verse.LongEventHandler:RunEventFromAnotherThread(Action)
Verse.<>c:<UpdateCurrentAsynchronousEvent>b__27_0()
System.Threading.ThreadHelper:ThreadStart_Context(Object)
System.Threading.ExecutionContext:RunInternal(ExecutionContext, ContextCallback, Object, Boolean)
System.Threading.ExecutionContext:Run(ExecutionContext, ContextCallback, Object, Boolean)
System.Threading.ExecutionContext:Run(ExecutionContext, ContextCallback, Object)
System.Threading.ThreadHelper:ThreadStart()


XML error: Could not find parent node named "BaseHumanGun" for node "ThingDef". Full node: <ThingDef Name="Gun_MG_42_RA" ParentName="BaseHumanGun"><defName>Gun_MG_42_RA</defName><label>Mounted MG 42</label><description>Designed to be low-cost and easy to build, the MG 42 proved to be highly reliable and easy to operate. It is most notable for its very high cyclic rate for a gun using full power service cartridges, averaging about 1,200 rounds per minute compared to around 850 for the MG 34, and perhaps 450 to 600 for other common machine guns like the M1919 Browning or Bren. This ability made it extremely effective in providing suppressive fire, and its unique sound led to it being nicknamed "Hitler's buzzsaw".</description><graphicData><texPath>Turret/MG_42/MG_42_Weapon</texPath><graphicClass>Graphic_Single</graphicClass></graphicData><soundInteract>Interact_Rifle</soundInteract><menuHidden>true</menuHidden><destroyOnDrop>true</destroyOnDrop><tradeability>None</tradeability><useHitPoints>false</useHitPoints><statBases><AccuracyTouch>0.45</AccuracyTouch><AccuracyShort>0.65</AccuracyShort><AccuracyMedium>0.80</AccuracyMedium><AccuracyLong>0.70</AccuracyLong><RangedWeapon_Cooldown>1.0</RangedWeapon_Cooldown><DeteriorationRate>0</DeteriorationRate><Mass>12</Mass><Flammability>0.5</Flammability></statBases><weaponTags Inherit="false"><li>TurretGun</li></weaponTags><verbs><li><verbClass>Verb_Shoot</verbClass><hasStandardCommand>true</hasStandardCommand><defaultProjectile>Bullet_792mm_MG_42_RA</defaultProjectile><warmupTime>1.6</warmupTime><range>37.0</range><ticksBetweenBurstShots>4</ticksBetweenBurstShots><burstShotCount>10</burstShotCount><soundCast>Shot_MG_42</soundCast><soundCastTail>GunTail_Heavy</soundCastTail><muzzleFlashScale>9</muzzleFlashScale><consumeFuelPerShot>0.5</consumeFuelPerShot></li></verbs></ThingDef>
Verse.Log:Error(String, Boolean)
Verse.XmlInheritance:GetBestParentFor(XmlInheritanceNode, String)
Verse.XmlInheritance:ResolveParentsAndChildNodesLinks()
Verse.XmlInheritance:Resolve()
Verse.LoadedModManager:ParseAndProcessXML(XmlDocument, Dictionary`2)
Verse.LoadedModManager:LoadAllActiveMods()
Verse.PlayDataLoader:DoPlayLoad()
Verse.PlayDataLoader:LoadAllPlayData(Boolean)
Verse.<>c:<Start>b__6_1()
Verse.LongEventHandler:RunEventFromAnotherThread(Action)
Verse.<>c:<UpdateCurrentAsynchronousEvent>b__27_0()
System.Threading.ThreadHelper:ThreadStart_Context(Object)
System.Threading.ExecutionContext:RunInternal(ExecutionContext, ContextCallback, Object, Boolean)
System.Threading.ExecutionContext:Run(ExecutionContext, ContextCallback, Object, Boolean)
System.Threading.ExecutionContext:Run(ExecutionContext, ContextCallback, Object)
System.Threading.ThreadHelper:ThreadStart()

