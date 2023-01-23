T-50 PAK FA
-----------


Features:
Detailed model
Breakable wings
Detailed cockpit
Openable weapon hatches
working artificial horizont, radar and engine power in cockpit
illuminated screens
working gear and wheels
working flaps
working nozzles
Bullet impacts and shattering glass
Proper LOD models



Credits:
Original model:
Battlefield 4

Textures, model reworking, converting:
SkylineGTRFreak

Afterburner script by: 
CamxxCore


To open the bomb bays, download CamxxCore's carpet bomber script:
https://www.gta5-mods.com/scripts/carpet-bomber


Also note: If you're going to make a video of this mod, please link my channel as well (https://www.youtube.com/user/SkylineGTRR34Freak). 
I know that some of you guys make a pretty buck off this and since I'm giving you these mods for free, a little support would be welcomed.


Installation:

Script:
You will need ScripthookV and scripthookDOTnet

After that, simply drag the "scripts" folder in your GTA V main folder.

The model files get into:
Update/x64/dlcpacks/patchday3ng/dlc.rpf/x64/levels/gta5/vehicles.rpf

DELETE the original lazer+hi.ytd file.

Edit vehicle.meta in:
update/update.rpf/common/data/levels/gta5

I will not include a vehicles.meta file itself. Editing one is not hard and it gives you an insight over what you're changing. Also, I often make a few mistakes in the .meta files and to prevent that, here is just the code.
Look up how to edit these files with Notepad++.

Here is a tutorial by Jeff Favignano:
https://www.youtube.com/watch?v=j0BO4JFwd_Y

<Item>
      <modelName>lazer</modelName>
      <txdName>lazer</txdName>
      <handlingId>LAZER</handlingId>
      <gameName>LAZER</gameName>
      <vehicleMakeName />
      <expressionDictName>null</expressionDictName>
      <expressionName>null</expressionName>
      <animConvRoofDictName>null</animConvRoofDictName>
      <animConvRoofName>null</animConvRoofName>
      <animConvRoofWindowsAffected />
      <ptfxAssetName>null</ptfxAssetName>
      <audioNameHash />
      <layout>LAYOUT_PLANE_STUNT</layout>
      <coverBoundOffsets>STANDARD_COVER_OFFSET_INFO</coverBoundOffsets>
      <explosionInfo>EXPLOSION_INFO_DEFAULT</explosionInfo>
      <scenarioLayout />
      <cameraName>FOLLOW_LAZER_CAMERA</cameraName>
      <aimCameraName>PLANE_AIM_CAMERA</aimCameraName>
      <bonnetCameraName>FIGHTER_BONNET_CAMERA</bonnetCameraName>
      <povCameraName>LAZER_POV_CAMERA</povCameraName>
      <FirstPersonDriveByIKOffset x="0.000000" y="0.000000" z="0.000000" />
      <FirstPersonDriveByUnarmedIKOffset x="0.000000" y="0.000000" z="0.000000" />
	  <FirstPersonProjectileDriveByIKOffset x="0.000000" y="0.000000" z="0.000000" />
	  <FirstPersonProjectileDriveByPassengerIKOffset x="0.000000" y="0.000000" z="0.000000" />
	  <FirstPersonProjectileDriveByRearLeftIKOffset x="0.000000" y="0.000000" z="0.000000" />
	  <FirstPersonProjectileDriveByRearRightIKOffset x="0.000000" y="0.000000" z="0.000000" />
	  <FirstPersonDriveByLeftPassengerIKOffset x="0.000000" y="0.000000" z="0.000000" />
	  <FirstPersonDriveByRightPassengerIKOffset x="0.000000" y="0.000000" z="0.000000" />
	  <FirstPersonDriveByRightRearPassengerIKOffset x="0.000000" y="0.000000" z="0.000000" />
	  <FirstPersonDriveByLeftPassengerUnarmedIKOffset x="0.000000" y="0.000000" z="0.000000" />
	  <FirstPersonDriveByRightPassengerUnarmedIKOffset x="0.000000" y="0.000000" z="0.000000" />
	  <FirstPersonMobilePhoneOffset x="0.133000" y="0.283000" z="0.558000" />
      <FirstPersonPassengerMobilePhoneOffset x="0.136000" y="0.223000" z="0.425000" />
      <PovCameraOffset x="0.000000" y="-0.165000" z="0.705000" />
      <PovCameraVerticalAdjustmentForRollCage value="0.000000" />
      <PovPassengerCameraOffset x="0.000000" y="0.000000" z="0.000000" />
      <PovRearPassengerCameraOffset x="0.000000" y="0.000000" z="0.000000" />
      <vfxInfoName>VFXVEHICLEINFO_PLANE_VULKAN</vfxInfoName>
      <shouldUseCinematicViewMode value="true" />
      <shouldCameraTransitionOnClimbUpDown value="false" />
      <shouldCameraIgnoreExiting value="false" />
      <AllowPretendOccupants value="false" />
      <AllowJoyriding value="true" />
      <AllowSundayDriving value="true" />
      <AllowBodyColorMapping value="true" />
      <wheelScale value="0.200100" />
      <wheelScaleRear value="0.117600" />
      <dirtLevelMin value="0.000000" />
      <dirtLevelMax value="0.000000" />
      <envEffScaleMin value="0.300000" />
      <envEffScaleMax value="0.600000" />
      <envEffScaleMin2 value="0.300000" />
      <envEffScaleMax2 value="0.500000" />
      <damageMapScale value="0.250000" />
      <damageOffsetScale value="0.250000" />
      <diffuseTint value="0x00FFFFFF" />
      <steerWheelMult value="1.000000" />
      <HDTextureDist value="5.000000" />
      <lodDistances content="float_array">
        100.000000
        400.000000
        600.000000
        1200.000000
        3400.000000
        3400.000000
      </lodDistances>
      <minSeatHeight value="0.897" />
      <identicalModelSpawnDistance value="20" />
      <maxNumOfSameColor value="10" />
      <defaultBodyHealth value="1000.000000" />
      <pretendOccupantsScale value="1.000000" />
      <visibleSpawnDistScale value="1.500000" />
      <trackerPathWidth value="2.000000" />
      <weaponForceMult value="1.000000" />
      <frequency value="100" />
      <swankness>SWANKNESS_4</swankness>
      <maxNum value="999" />
      <flags>FLAG_NO_BOOT FLAG_HAS_LIVERY FLAG_DRIVER_NO_DRIVE_BY FLAG_DONT_SPAWN_IN_CARGEN FLAG_DONT_SPAWN_AS_AMBIENT FLAG_HEADLIGHTS_ON_LANDINGGEAR FLAG_BLOCK_FROM_ATTRACTOR_SCENARIO FLAG_DONT_TIMESLICE_WHEELS FLAG_DISABLE_WEAPON_WHEEL_IN_FIRST_PERSON FLAG_USE_WEAPON_WHEEL_WITHOUT_HELMET FLAG_USE_PILOT_HELMET</flags>
      <type>VEHICLE_TYPE_PLANE</type>
      <plateType>VPT_NONE</plateType>
      <dashboardType>VDT_LAZER</dashboardType>
      <vehicleClass>VC_PLANE</vehicleClass>
      <wheelType>VWT_SPORT</wheelType>
      <trailers />
      <additionalTrailers />
      <drivers>
        <Item>
          <driverName>S_M_M_Marine_02</driverName>
          <npcName />
        </Item>
      </drivers>
      <extraIncludes />
      <doorsWithCollisionWhenClosed>
        <Item>VEH_EXT_DOOR_DSIDE_F</Item>
      </doorsWithCollisionWhenClosed>
      <driveableDoors>
        <Item>VEH_EXT_DOOR_PSIDE_F</Item>
        <Item>VEH_EXT_BONNET</Item>
		<Item>VEH_EXT_DOOR_PSIDE_R</Item>
		<Item>VEH_EXT_DOOR_DSIDE_R</Item>
		<Item>VEH_EXT_BOOT</Item>
      </driveableDoors>
      <bumpersNeedToCollideWithMap value="false" />
      <needsRopeTexture value="false" />
      <requiredExtras />
      <rewards />
      <cinematicPartCamera>
        <Item>WINGTIP_LEFT_CAMERA</Item>
        <Item>WINGTIP_RIGHT_CAMERA</Item>
        <Item>LAZER_TAIL_RIGHT_CAMERA</Item>
      </cinematicPartCamera>
      <NmBraceOverrideSet />
      <buoyancySphereOffset x="0.000000" y="0.000000" z="0.000000" />
      <buoyancySphereSizeScale value="1.000000" />
      <pOverrideRagdollThreshold type="NULL" />
      <firstPersonDrivebyData>
        <Item>STD_FRONT_LEFT</Item>
      </firstPersonDrivebyData>
    </Item>





This goes into handling.meta (update/update.rpf/common/data):

<Item type="CHandlingData">
      <handlingName>LAZER</handlingName>
      <fMass value="8000.000000" />
      <fInitialDragCoeff value="2.000000" />
      <fPercentSubmerged value="75.000000" />
      <vecCentreOfMassOffset x="0.000000" y="0.000000" z="0.000000" />
      <vecInertiaMultiplier x="1.000000" y="1.000000" z="1.000000" />
      <fDriveBiasFront value="1.000000" />
      <nInitialDriveGears value="1" />
      <fInitialDriveForce value="0.001000" />
      <fDriveInertia value="1.000000" />
      <fClutchChangeRateScaleUpShift value="1.300000" />
      <fClutchChangeRateScaleDownShift value="1.300000" />
      <fInitialDriveMaxFlatVel value="328.600000" />
      <fBrakeForce value="0.050000" />
      <fBrakeBiasFront value="0.600000" />
      <fHandBrakeForce value="0.700000" />
      <fSteeringLock value="30.000000" />
      <fTractionCurveMax value="2.150000" />
      <fTractionCurveMin value="1.800000" />
      <fTractionCurveLateral value="12.000000" />
      <fTractionSpringDeltaMax value="0.100000" />
      <fLowSpeedTractionLossMult value="0.000000" />
      <fCamberStiffnesss value="0.000000" />
      <fTractionBiasFront value="0.500000" />
      <fTractionLossMult value="1.000000" />
      <fSuspensionForce value="6.500000" />
      <fSuspensionCompDamp value="6.800000" />
      <fSuspensionReboundDamp value="6.800000" />
      <fSuspensionUpperLimit value="0.060000" />
      <fSuspensionLowerLimit value="-0.060000" />
      <fSuspensionRaise value="0.000000" />
      <fSuspensionBiasFront value="0.600000" />
      <fAntiRollBarForce value="0.000000" />
      <fAntiRollBarBiasFront value="0.000000" />
      <fRollCentreHeightFront value="0.000000" />
      <fRollCentreHeightRear value="0.000000" />
      <fCollisionDamageMult value="1.500000" />
      <fWeaponDamageMult value="0.500000" />
      <fDeformationDamageMult value="4.000000" />
      <fEngineDamageMult value="1.500000" />
      <fPetrolTankVolume value="65.000000" />
      <fOilVolume value="5.000000" />
      <fSeatOffsetDistX value="0.000000" />
      <fSeatOffsetDistY value="0.000000" />
      <fSeatOffsetDistZ value="-1.000000" />
      <nMonetaryValue value="45000" />
      <strModelFlags>1000000</strModelFlags>
      <strHandlingFlags>400100</strHandlingFlags>
      <strDamageFlags>20</strDamageFlags>
      <AIHandling>AVERAGE</AIHandling>
      <SubHandlingData>
        <Item type="CFlyingHandlingData">
          <fThrust value="2.000000" />
          <fThrustFallOff value="0.000120" />
          <fThrustVectoring value="0.000000" />
          <fYawMult value="-0.001000" />
          <fYawStabilise value="0.002000" />
          <fSideSlipMult value="0.050000" />
          <fRollMult value="0.009000" />
          <fRollStabilise value="-0.000000" />
          <fPitchMult value="0.002000" />
          <fPitchStabilise value="0.001000" />
          <fFormLiftMult value="0.000150" />
          <fAttackLiftMult value="0.018000" />
          <fAttackDiveMult value="0.025000" />
          <fGearDownDragV value="0.100000" />
          <fGearDownLiftMult value="0.600000" />
          <fWindMult value="0.120000" />
          <fMoveRes value="0.010000" />
          <vecTurnRes x="0.050000" y="0.500000" z="0.400000" />
          <vecSpeedRes x="0.020000" y="0.250000" z="0.015000" />
          <fGearDoorFrontOpen value="85.000000" />
          <fGearDoorRearOpen value="20.000000" />
          <fGearDoorRearOpen2 value="-75.000000" />
          <fGearDoorRearMOpen value="-15.000000" />
          <fTurublenceMagnitudeMax value="10.000000" />
          <fTurublenceForceMulti value="0.000500" />
          <fTurublenceRollTorqueMulti value="0.035000" />
          <fTurublencePitchTorqueMulti value="0.000000" />
          <fBodyDamageControlEffectMult value="0.100000" />
          <fInputSensitivityForDifficulty value="3.000000" />
          <fOnGroundYawBoostSpeedPeak value="3.000000" />
          <fOnGroundYawBoostSpeedCap value="6.000000" />
          <fEngineOffGlideMulti value="0.100000" />
          <handlingType>HANDLING_TYPE_FLYING</handlingType>
        </Item>
        <Item type="CVehicleWeaponHandlingData">
          <uWeaponHash>
            <Item>VEHICLE_WEAPON_PLAYER_LAZER</Item>
            <Item>VEHICLE_WEAPON_PLANE_ROCKET</Item>
            <Item />
          </uWeaponHash>
          <WeaponSeats content="int_array">
            0 
            0 
            0 
          </WeaponSeats>
          <fTurretSpeed content="float_array">
            0.000000	
            0.000000	
          </fTurretSpeed>
          <fTurretPitchMin content="float_array">
            0.000000	
            0.000000	
          </fTurretPitchMin>
          <fTurretPitchMax content="float_array">
            0.000000	
            0.000000	
          </fTurretPitchMax>
          <fTurretCamPitchMin content="float_array">
            0.000000	
            0.000000	
          </fTurretCamPitchMin>
          <fTurretCamPitchMax content="float_array">
            0.000000	
            0.000000	
          </fTurretCamPitchMax>
          <fBulletVelocityForGravity content="float_array">
            0.000000	
            0.000000	
          </fBulletVelocityForGravity>
          <fTurretPitchForwardMin content="float_array">
            0.000000	
            0.000000	
          </fTurretPitchForwardMin>
          <fUvAnimationMult value="0.000000" />
          <fMiscGadgetVar value="0.000000" />
          <fWheelImpactOffset value="0.000000" />
        </Item>
        <Item type="NULL" />
      </SubHandlingData>
    </Item>