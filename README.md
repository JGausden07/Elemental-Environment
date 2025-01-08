%YAML 1.1
%TAG !u! tag:unity3d.com,2011:
--- !u!29 &1
OcclusionCullingSettings:
  m_ObjectHideFlags: 0
  serializedVersion: 2
  m_OcclusionBakeSettings:
    smallestOccluder: 5
    smallestHole: 0.25
    backfaceThreshold: 100
  m_SceneGUID: 00000000000000000000000000000000
  m_OcclusionCullingData: {fileID: 0}
--- !u!104 &2
RenderSettings:
  m_ObjectHideFlags: 0
  serializedVersion: 9
  m_Fog: 0
  m_FogColor: {r: 0.5, g: 0.5, b: 0.5, a: 1}
  m_FogMode: 3
  m_FogDensity: 0.01
  m_LinearFogStart: 0
  m_LinearFogEnd: 300
  m_AmbientSkyColor: {r: 0.212, g: 0.227, b: 0.259, a: 1}
  m_AmbientEquatorColor: {r: 0.114, g: 0.125, b: 0.133, a: 1}
  m_AmbientGroundColor: {r: 0.047, g: 0.043, b: 0.035, a: 1}
  m_AmbientIntensity: 1
  m_AmbientMode: 0
  m_SubtractiveShadowColor: {r: 0.42, g: 0.478, b: 0.627, a: 1}
  m_SkyboxMaterial: {fileID: 10304, guid: 0000000000000000f000000000000000, type: 0}
  m_HaloStrength: 0.5
  m_FlareStrength: 1
  m_FlareFadeSpeed: 3
  m_HaloTexture: {fileID: 0}
  m_SpotCookie: {fileID: 10001, guid: 0000000000000000e000000000000000, type: 0}
  m_DefaultReflectionMode: 0
  m_DefaultReflectionResolution: 128
  m_ReflectionBounces: 1
  m_ReflectionIntensity: 1
  m_CustomReflection: {fileID: 0}
  m_Sun: {fileID: 705507994}
  m_IndirectSpecularColor: {r: 0.44657898, g: 0.4964133, b: 0.5748178, a: 1}
  m_UseRadianceAmbientProbe: 0
--- !u!157 &3
LightmapSettings:
  m_ObjectHideFlags: 0
  serializedVersion: 12
  m_GIWorkflowMode: 1
  m_GISettings:
    serializedVersion: 2
    m_BounceScale: 1
    m_IndirectOutputScale: 1
    m_AlbedoBoost: 1
    m_EnvironmentLightingMode: 0
    m_EnableBakedLightmaps: 1
    m_EnableRealtimeLightmaps: 0
  m_LightmapEditorSettings:
    serializedVersion: 12
    m_Resolution: 2
    m_BakeResolution: 40
    m_AtlasSize: 1024
    m_AO: 0
    m_AOMaxDistance: 1
    m_CompAOExponent: 1
    m_CompAOExponentDirect: 0
    m_ExtractAmbientOcclusion: 0
    m_Padding: 2
    m_LightmapParameters: {fileID: 0}
    m_LightmapsBakeMode: 1
    m_TextureCompression: 1
    m_FinalGather: 0
    m_FinalGatherFiltering: 1
    m_FinalGatherRayCount: 256
    m_ReflectionCompression: 2
    m_MixedBakeMode: 2
    m_BakeBackend: 1
    m_PVRSampling: 1
    m_PVRDirectSampleCount: 32
    m_PVRSampleCount: 500
    m_PVRBounces: 2
    m_PVREnvironmentSampleCount: 500
    m_PVREnvironmentReferencePointCount: 2048
    m_PVRFilteringMode: 2
    m_PVRDenoiserTypeDirect: 0
    m_PVRDenoiserTypeIndirect: 0
    m_PVRDenoiserTypeAO: 0
    m_PVRFilterTypeDirect: 0
    m_PVRFilterTypeIndirect: 0
    m_PVRFilterTypeAO: 0
    m_PVREnvironmentMIS: 0
    m_PVRCulling: 1
    m_PVRFilteringGaussRadiusDirect: 1
    m_PVRFilteringGaussRadiusIndirect: 5
    m_PVRFilteringGaussRadiusAO: 2
    m_PVRFilteringAtrousPositionSigmaDirect: 0.5
    m_PVRFilteringAtrousPositionSigmaIndirect: 2
    m_PVRFilteringAtrousPositionSigmaAO: 1
    m_ExportTrainingData: 0
    m_TrainingDataDestination: TrainingData
    m_LightProbeSampleCountMultiplier: 4
  m_LightingDataAsset: {fileID: 0}
  m_LightingSettings: {fileID: 0}
--- !u!196 &4
NavMeshSettings:
  serializedVersion: 2
  m_ObjectHideFlags: 0
  m_BuildSettings:
    serializedVersion: 3
    agentTypeID: 0
    agentRadius: 0.5
    agentHeight: 2
    agentSlope: 45
    agentClimb: 0.4
    ledgeDropHeight: 0
    maxJumpAcrossDistance: 0
    minRegionArea: 2
    manualCellSize: 0
    cellSize: 0.16666667
    manualTileSize: 0
    tileSize: 256
    buildHeightMesh: 0
    maxJobWorkers: 0
    preserveTilesOutsideBounds: 0
    debug:
      m_Flags: 0
  m_NavMeshData: {fileID: 0}
--- !u!1 &284065637
GameObject:
  m_ObjectHideFlags: 0
  m_CorrespondingSourceObject: {fileID: 0}
  m_PrefabInstance: {fileID: 0}
  m_PrefabAsset: {fileID: 0}
  serializedVersion: 6
  m_Component:
  - component: {fileID: 284065639}
  - component: {fileID: 284065638}
  m_Layer: 0
  m_Name: Point Light (3)
  m_TagString: Untagged
  m_Icon: {fileID: 0}
  m_NavMeshLayer: 0
  m_StaticEditorFlags: 0
  m_IsActive: 1
--- !u!108 &284065638
Light:
  m_ObjectHideFlags: 0
  m_CorrespondingSourceObject: {fileID: 0}
  m_PrefabInstance: {fileID: 0}
  m_PrefabAsset: {fileID: 0}
  m_GameObject: {fileID: 284065637}
  m_Enabled: 1
  serializedVersion: 10
  m_Type: 2
  m_Shape: 0
  m_Color: {r: 1, g: 0.4411648, b: 0, a: 1}
  m_Intensity: 63
  m_Range: 55.23
  m_SpotAngle: 30
  m_InnerSpotAngle: 21.80208
  m_CookieSize: 10
  m_Shadows:
    m_Type: 0
    m_Resolution: -1
    m_CustomResolution: -1
    m_Strength: 1
    m_Bias: 0.05
    m_NormalBias: 0.4
    m_NearPlane: 0.2
    m_CullingMatrixOverride:
      e00: 1
      e01: 0
      e02: 0
      e03: 0
      e10: 0
      e11: 1
      e12: 0
      e13: 0
      e20: 0
      e21: 0
      e22: 1
      e23: 0
      e30: 0
      e31: 0
      e32: 0
      e33: 1
    m_UseCullingMatrixOverride: 0
  m_Cookie: {fileID: 0}
  m_DrawHalo: 0
  m_Flare: {fileID: 0}
  m_RenderMode: 0
  m_CullingMask:
    serializedVersion: 2
    m_Bits: 4294967295
  m_RenderingLayerMask: 1
  m_Lightmapping: 4
  m_LightShadowCasterMode: 0
  m_AreaSize: {x: 1, y: 1}
  m_BounceIntensity: 1
  m_ColorTemperature: 6570
  m_UseColorTemperature: 0
  m_BoundingSphereOverride: {x: 0, y: 0, z: 0, w: 0}
  m_UseBoundingSphereOverride: 0
  m_UseViewFrustumForShadowCasterCull: 1
  m_ShadowRadius: 0
  m_ShadowAngle: 0
--- !u!4 &284065639
Transform:
  m_ObjectHideFlags: 0
  m_CorrespondingSourceObject: {fileID: 0}
  m_PrefabInstance: {fileID: 0}
  m_PrefabAsset: {fileID: 0}
  m_GameObject: {fileID: 284065637}
  serializedVersion: 2
  m_LocalRotation: {x: 0, y: 0, z: 0, w: 1}
  m_LocalPosition: {x: 2.9, y: 103.35, z: -29.9}
  m_LocalScale: {x: 1, y: 1, z: 1}
  m_ConstrainProportionsScale: 0
  m_Children: []
  m_Father: {fileID: 0}
  m_LocalEulerAnglesHint: {x: 0, y: 0, z: 0}
--- !u!1 &529940561
GameObject:
  m_ObjectHideFlags: 0
  m_CorrespondingSourceObject: {fileID: 0}
  m_PrefabInstance: {fileID: 0}
  m_PrefabAsset: {fileID: 0}
  serializedVersion: 6
  m_Component:
  - component: {fileID: 529940564}
  - component: {fileID: 529940563}
  - component: {fileID: 529940562}
  m_Layer: 0
  m_Name: Particle System (2)
  m_TagString: Untagged
  m_Icon: {fileID: 0}
  m_NavMeshLayer: 0
  m_StaticEditorFlags: 0
  m_IsActive: 1
--- !u!199 &529940562
ParticleSystemRenderer:
  serializedVersion: 6
  m_ObjectHideFlags: 0
  m_CorrespondingSourceObject: {fileID: 0}
  m_PrefabInstance: {fileID: 0}
  m_PrefabAsset: {fileID: 0}
  m_GameObject: {fileID: 529940561}
  m_Enabled: 1
  m_CastShadows: 0
  m_ReceiveShadows: 0
  m_DynamicOccludee: 1
  m_StaticShadowCaster: 0
  m_MotionVectors: 1
  m_LightProbeUsage: 0
  m_ReflectionProbeUsage: 0
  m_RayTracingMode: 0
  m_RayTraceProcedural: 0
  m_RenderingLayerMask: 1
  m_RendererPriority: 0
  m_Materials:
  - {fileID: 10308, guid: 0000000000000000f000000000000000, type: 0}
  m_StaticBatchInfo:
    firstSubMesh: 0
    subMeshCount: 0
  m_StaticBatchRoot: {fileID: 0}
  m_ProbeAnchor: {fileID: 0}
  m_LightProbeVolumeOverride: {fileID: 0}
  m_ScaleInLightmap: 1
  m_ReceiveGI: 1
  m_PreserveUVs: 0
  m_IgnoreNormalsForChartDetection: 0
  m_ImportantGI: 0
  m_StitchLightmapSeams: 1
  m_SelectedEditorRenderState: 3
  m_MinimumChartSize: 4
  m_AutoUVMaxDistance: 0.5
  m_AutoUVMaxAngle: 89
  m_LightmapParameters: {fileID: 0}
  m_SortingLayerID: 0
  m_SortingLayer: 0
  m_SortingOrder: 0
  m_RenderMode: 0
  m_MeshDistribution: 0
  m_SortMode: 0
  m_MinParticleSize: 0
  m_MaxParticleSize: 0.5
  m_CameraVelocityScale: 0
  m_VelocityScale: 0
  m_LengthScale: 2
  m_SortingFudge: 0
  m_NormalDirection: 1
  m_ShadowBias: 0
  m_RenderAlignment: 0
  m_Pivot: {x: 0, y: 0, z: 0}
  m_Flip: {x: 0, y: 0, z: 0}
  m_UseCustomVertexStreams: 0
  m_EnableGPUInstancing: 1
  m_ApplyActiveColorSpace: 1
  m_AllowRoll: 1
  m_FreeformStretching: 0
  m_RotateWithStretchDirection: 1
  m_VertexStreams: 00010304
  m_Mesh: {fileID: 0}
  m_Mesh1: {fileID: 0}
  m_Mesh2: {fileID: 0}
  m_Mesh3: {fileID: 0}
  m_MeshWeighting: 1
  m_MeshWeighting1: 1
  m_MeshWeighting2: 1
  m_MeshWeighting3: 1
  m_MaskInteraction: 0
--- !u!198 &529940563
ParticleSystem:
  m_ObjectHideFlags: 0
  m_CorrespondingSourceObject: {fileID: 0}
  m_PrefabInstance: {fileID: 0}
  m_PrefabAsset: {fileID: 0}
  m_GameObject: {fileID: 529940561}
  serializedVersion: 8
  lengthInSec: 5
  simulationSpeed: 1
  stopAction: 0
  cullingMode: 0
  ringBufferMode: 0
  ringBufferLoopRange: {x: 0, y: 1}
  emitterVelocityMode: 1
  looping: 1
  prewarm: 0
  playOnAwake: 1
  useUnscaledTime: 0
  autoRandomSeed: 1
  startDelay:
    serializedVersion: 2
    minMaxState: 0
    scalar: 0
    minScalar: 0
    maxCurve:
      serializedVersion: 2
      m_Curve:
      - serializedVersion: 3
        time: 0
        value: 0
        inSlope: 0
        outSlope: 0
        tangentMode: 0
        weightedMode: 0
        inWeight: 0.33333334
        outWeight: 0.33333334
      - serializedVersion: 3
        time: 1
        value: 0
        inSlope: 0
        outSlope: 0
        tangentMode: 0
        weightedMode: 0
        inWeight: 0.33333334
        outWeight: 0.33333334
      m_PreInfinity: 2
      m_PostInfinity: 2
      m_RotationOrder: 4
    minCurve:
      serializedVersion: 2
      m_Curve:
      - serializedVersion: 3
        time: 0
        value: 0
        inSlope: 0
        outSlope: 0
        tangentMode: 0
        weightedMode: 0
        inWeight: 0.33333334
        outWeight: 0.33333334
      - serializedVersion: 3
        time: 1
        value: 0
        inSlope: 0
        outSlope: 0
        tangentMode: 0
        weightedMode: 0
        inWeight: 0.33333334
        outWeight: 0.33333334
      m_PreInfinity: 2
      m_PostInfinity: 2
      m_RotationOrder: 4
  moveWithTransform: 0
  moveWithCustomTransform: {fileID: 0}
  scalingMode: 1
  randomSeed: 0
  InitialModule:
    serializedVersion: 3
    enabled: 1
    startLifetime:
      serializedVersion: 2
      minMaxState: 0
      scalar: 5
      minScalar: 5
      maxCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
      minCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
    startSpeed:
      serializedVersion: 2
      minMaxState: 0
      scalar: 5
      minScalar: 5
      maxCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
      minCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
    startColor:
      serializedVersion: 2
      minMaxState: 0
      minColor: {r: 1, g: 1, b: 1, a: 1}
      maxColor: {r: 1, g: 0.5061273, b: 0, a: 1}
      maxGradient:
        serializedVersion: 2
        key0: {r: 1, g: 1, b: 1, a: 1}
        key1: {r: 1, g: 1, b: 1, a: 1}
        key2: {r: 0, g: 0, b: 0, a: 0}
        key3: {r: 0, g: 0, b: 0, a: 0}
        key4: {r: 0, g: 0, b: 0, a: 0}
        key5: {r: 0, g: 0, b: 0, a: 0}
        key6: {r: 0, g: 0, b: 0, a: 0}
        key7: {r: 0, g: 0, b: 0, a: 0}
        ctime0: 0
        ctime1: 65535
        ctime2: 0
        ctime3: 0
        ctime4: 0
        ctime5: 0
        ctime6: 0
        ctime7: 0
        atime0: 0
        atime1: 65535
        atime2: 0
        atime3: 0
        atime4: 0
        atime5: 0
        atime6: 0
        atime7: 0
        m_Mode: 0
        m_ColorSpace: -1
        m_NumColorKeys: 2
        m_NumAlphaKeys: 2
      minGradient:
        serializedVersion: 2
        key0: {r: 1, g: 1, b: 1, a: 1}
        key1: {r: 1, g: 1, b: 1, a: 1}
        key2: {r: 0, g: 0, b: 0, a: 0}
        key3: {r: 0, g: 0, b: 0, a: 0}
        key4: {r: 0, g: 0, b: 0, a: 0}
        key5: {r: 0, g: 0, b: 0, a: 0}
        key6: {r: 0, g: 0, b: 0, a: 0}
        key7: {r: 0, g: 0, b: 0, a: 0}
        ctime0: 0
        ctime1: 65535
        ctime2: 0
        ctime3: 0
        ctime4: 0
        ctime5: 0
        ctime6: 0
        ctime7: 0
        atime0: 0
        atime1: 65535
        atime2: 0
        atime3: 0
        atime4: 0
        atime5: 0
        atime6: 0
        atime7: 0
        m_Mode: 0
        m_ColorSpace: -1
        m_NumColorKeys: 2
        m_NumAlphaKeys: 2
    startSize:
      serializedVersion: 2
      minMaxState: 0
      scalar: 1
      minScalar: 1
      maxCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
      minCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
    startSizeY:
      serializedVersion: 2
      minMaxState: 0
      scalar: 1
      minScalar: 1
      maxCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
      minCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
    startSizeZ:
      serializedVersion: 2
      minMaxState: 0
      scalar: 1
      minScalar: 1
      maxCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
      minCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
    startRotationX:
      serializedVersion: 2
      minMaxState: 0
      scalar: 0
      minScalar: 0
      maxCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
      minCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
    startRotationY:
      serializedVersion: 2
      minMaxState: 0
      scalar: 0
      minScalar: 0
      maxCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
      minCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
    startRotation:
      serializedVersion: 2
      minMaxState: 0
      scalar: 0
      minScalar: 0
      maxCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
      minCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
    randomizeRotationDirection: 0
    gravitySource: 0
    maxNumParticles: 1000
    customEmitterVelocity: {x: 0, y: 0, z: 0}
    size3D: 0
    rotation3D: 0
    gravityModifier:
      serializedVersion: 2
      minMaxState: 0
      scalar: 0
      minScalar: 0
      maxCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
      minCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
  ShapeModule:
    serializedVersion: 6
    enabled: 1
    type: 4
    angle: 25
    length: 5
    boxThickness: {x: 0, y: 0, z: 0}
    radiusThickness: 1
    donutRadius: 0.2
    m_Position: {x: 0, y: 0, z: 0}
    m_Rotation: {x: 0, y: 0, z: 0}
    m_Scale: {x: 1, y: 1, z: 1}
    placementMode: 0
    m_MeshMaterialIndex: 0
    m_MeshNormalOffset: 0
    m_MeshSpawn:
      mode: 0
      spread: 0
      speed:
        serializedVersion: 2
        minMaxState: 0
        scalar: 1
        minScalar: 1
        maxCurve:
          serializedVersion: 2
          m_Curve:
          - serializedVersion: 3
            time: 0
            value: 1
            inSlope: 0
            outSlope: 0
            tangentMode: 0
            weightedMode: 0
            inWeight: 0.33333334
            outWeight: 0.33333334
          - serializedVersion: 3
            time: 1
            value: 1
            inSlope: 0
            outSlope: 0
            tangentMode: 0
            weightedMode: 0
            inWeight: 0.33333334
            outWeight: 0.33333334
          m_PreInfinity: 2
          m_PostInfinity: 2
          m_RotationOrder: 4
        minCurve:
          serializedVersion: 2
          m_Curve:
          - serializedVersion: 3
            time: 0
            value: 1
            inSlope: 0
            outSlope: 0
            tangentMode: 0
            weightedMode: 0
            inWeight: 0.33333334
            outWeight: 0.33333334
          - serializedVersion: 3
            time: 1
            value: 1
            inSlope: 0
            outSlope: 0
            tangentMode: 0
            weightedMode: 0
            inWeight: 0.33333334
            outWeight: 0.33333334
          m_PreInfinity: 2
          m_PostInfinity: 2
          m_RotationOrder: 4
    m_Mesh: {fileID: 0}
    m_MeshRenderer: {fileID: 0}
    m_SkinnedMeshRenderer: {fileID: 0}
    m_Sprite: {fileID: 0}
    m_SpriteRenderer: {fileID: 0}
    m_UseMeshMaterialIndex: 0
    m_UseMeshColors: 1
    alignToDirection: 0
    m_Texture: {fileID: 0}
    m_TextureClipChannel: 3
    m_TextureClipThreshold: 0
    m_TextureUVChannel: 0
    m_TextureColorAffectsParticles: 1
    m_TextureAlphaAffectsParticles: 1
    m_TextureBilinearFiltering: 0
    randomDirectionAmount: 0
    sphericalDirectionAmount: 0
    randomPositionAmount: 0
    radius:
      value: 1
      mode: 0
      spread: 0
      speed:
        serializedVersion: 2
        minMaxState: 0
        scalar: 1
        minScalar: 1
        maxCurve:
          serializedVersion: 2
          m_Curve:
          - serializedVersion: 3
            time: 0
            value: 1
            inSlope: 0
            outSlope: 0
            tangentMode: 0
            weightedMode: 0
            inWeight: 0.33333334
            outWeight: 0.33333334
          - serializedVersion: 3
            time: 1
            value: 1
            inSlope: 0
            outSlope: 0
            tangentMode: 0
            weightedMode: 0
            inWeight: 0.33333334
            outWeight: 0.33333334
          m_PreInfinity: 2
          m_PostInfinity: 2
          m_RotationOrder: 4
        minCurve:
          serializedVersion: 2
          m_Curve:
          - serializedVersion: 3
            time: 0
            value: 1
            inSlope: 0
            outSlope: 0
            tangentMode: 0
            weightedMode: 0
            inWeight: 0.33333334
            outWeight: 0.33333334
          - serializedVersion: 3
            time: 1
            value: 1
            inSlope: 0
            outSlope: 0
            tangentMode: 0
            weightedMode: 0
            inWeight: 0.33333334
            outWeight: 0.33333334
          m_PreInfinity: 2
          m_PostInfinity: 2
          m_RotationOrder: 4
    arc:
      value: 360
      mode: 0
      spread: 0
      speed:
        serializedVersion: 2
        minMaxState: 0
        scalar: 1
        minScalar: 1
        maxCurve:
          serializedVersion: 2
          m_Curve:
          - serializedVersion: 3
            time: 0
            value: 1
            inSlope: 0
            outSlope: 0
            tangentMode: 0
            weightedMode: 0
            inWeight: 0.33333334
            outWeight: 0.33333334
          - serializedVersion: 3
            time: 1
            value: 1
            inSlope: 0
            outSlope: 0
            tangentMode: 0
            weightedMode: 0
            inWeight: 0.33333334
            outWeight: 0.33333334
          m_PreInfinity: 2
          m_PostInfinity: 2
          m_RotationOrder: 4
        minCurve:
          serializedVersion: 2
          m_Curve:
          - serializedVersion: 3
            time: 0
            value: 1
            inSlope: 0
            outSlope: 0
            tangentMode: 0
            weightedMode: 0
            inWeight: 0.33333334
            outWeight: 0.33333334
          - serializedVersion: 3
            time: 1
            value: 1
            inSlope: 0
            outSlope: 0
            tangentMode: 0
            weightedMode: 0
            inWeight: 0.33333334
            outWeight: 0.33333334
          m_PreInfinity: 2
          m_PostInfinity: 2
          m_RotationOrder: 4
  EmissionModule:
    enabled: 1
    serializedVersion: 4
    rateOverTime:
      serializedVersion: 2
      minMaxState: 0
      scalar: 10
      minScalar: 10
      maxCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
      minCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
    rateOverDistance:
      serializedVersion: 2
      minMaxState: 0
      scalar: 0
      minScalar: 0
      maxCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
      minCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
    m_BurstCount: 0
    m_Bursts: []
  SizeModule:
    enabled: 0
    curve:
      serializedVersion: 2
      minMaxState: 1
      scalar: 1
      minScalar: 1
      maxCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 0
          inSlope: 0
          outSlope: 1
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 1
          inSlope: 1
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
      minCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
    y:
      serializedVersion: 2
      minMaxState: 1
      scalar: 1
      minScalar: 1
      maxCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 0
          inSlope: 0
          outSlope: 1
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 1
          inSlope: 1
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
      minCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
    z:
      serializedVersion: 2
      minMaxState: 1
      scalar: 1
      minScalar: 1
      maxCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 0
          inSlope: 0
          outSlope: 1
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 1
          inSlope: 1
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
      minCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
    separateAxes: 0
  RotationModule:
    enabled: 0
    x:
      serializedVersion: 2
      minMaxState: 0
      scalar: 0
      minScalar: 0
      maxCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
      minCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
    y:
      serializedVersion: 2
      minMaxState: 0
      scalar: 0
      minScalar: 0
      maxCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
      minCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
    curve:
      serializedVersion: 2
      minMaxState: 0
      scalar: 0.7853982
      minScalar: 0.7853982
      maxCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
      minCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
    separateAxes: 0
  ColorModule:
    enabled: 0
    gradient:
      serializedVersion: 2
      minMaxState: 1
      minColor: {r: 1, g: 1, b: 1, a: 1}
      maxColor: {r: 1, g: 1, b: 1, a: 1}
      maxGradient:
        serializedVersion: 2
        key0: {r: 1, g: 1, b: 1, a: 1}
        key1: {r: 1, g: 1, b: 1, a: 1}
        key2: {r: 0, g: 0, b: 0, a: 0}
        key3: {r: 0, g: 0, b: 0, a: 0}
        key4: {r: 0, g: 0, b: 0, a: 0}
        key5: {r: 0, g: 0, b: 0, a: 0}
        key6: {r: 0, g: 0, b: 0, a: 0}
        key7: {r: 0, g: 0, b: 0, a: 0}
        ctime0: 0
        ctime1: 65535
        ctime2: 0
        ctime3: 0
        ctime4: 0
        ctime5: 0
        ctime6: 0
        ctime7: 0
        atime0: 0
        atime1: 65535
        atime2: 0
        atime3: 0
        atime4: 0
        atime5: 0
        atime6: 0
        atime7: 0
        m_Mode: 0
        m_ColorSpace: -1
        m_NumColorKeys: 2
        m_NumAlphaKeys: 2
      minGradient:
        serializedVersion: 2
        key0: {r: 1, g: 1, b: 1, a: 1}
        key1: {r: 1, g: 1, b: 1, a: 1}
        key2: {r: 0, g: 0, b: 0, a: 0}
        key3: {r: 0, g: 0, b: 0, a: 0}
        key4: {r: 0, g: 0, b: 0, a: 0}
        key5: {r: 0, g: 0, b: 0, a: 0}
        key6: {r: 0, g: 0, b: 0, a: 0}
        key7: {r: 0, g: 0, b: 0, a: 0}
        ctime0: 0
        ctime1: 65535
        ctime2: 0
        ctime3: 0
        ctime4: 0
        ctime5: 0
        ctime6: 0
        ctime7: 0
        atime0: 0
        atime1: 65535
        atime2: 0
        atime3: 0
        atime4: 0
        atime5: 0
        atime6: 0
        atime7: 0
        m_Mode: 0
        m_ColorSpace: -1
        m_NumColorKeys: 2
        m_NumAlphaKeys: 2
  UVModule:
    serializedVersion: 2
    enabled: 0
    mode: 0
    timeMode: 0
    fps: 30
    frameOverTime:
      serializedVersion: 2
      minMaxState: 1
      scalar: 0.9999
      minScalar: 0.9999
      maxCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 0
          inSlope: 0
          outSlope: 1
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 1
          inSlope: 1
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
      minCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
    startFrame:
      serializedVersion: 2
      minMaxState: 0
      scalar: 0
      minScalar: 0
      maxCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
      minCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
    speedRange: {x: 0, y: 1}
    tilesX: 1
    tilesY: 1
    animationType: 0
    rowIndex: 0
    cycles: 1
    uvChannelMask: -1
    rowMode: 1
    sprites:
    - sprite: {fileID: 0}
    flipU: 0
    flipV: 0
  VelocityModule:
    enabled: 0
    x:
      serializedVersion: 2
      minMaxState: 0
      scalar: 0
      minScalar: 0
      maxCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
      minCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
    y:
      serializedVersion: 2
      minMaxState: 0
      scalar: 0
      minScalar: 0
      maxCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
      minCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
    z:
      serializedVersion: 2
      minMaxState: 0
      scalar: 0
      minScalar: 0
      maxCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
      minCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
    orbitalX:
      serializedVersion: 2
      minMaxState: 0
      scalar: 0
      minScalar: 0
      maxCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
      minCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
    orbitalY:
      serializedVersion: 2
      minMaxState: 0
      scalar: 0
      minScalar: 0
      maxCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
      minCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
    orbitalZ:
      serializedVersion: 2
      minMaxState: 0
      scalar: 0
      minScalar: 0
      maxCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
      minCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
    orbitalOffsetX:
      serializedVersion: 2
      minMaxState: 0
      scalar: 0
      minScalar: 0
      maxCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
      minCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
    orbitalOffsetY:
      serializedVersion: 2
      minMaxState: 0
      scalar: 0
      minScalar: 0
      maxCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
      minCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
    orbitalOffsetZ:
      serializedVersion: 2
      minMaxState: 0
      scalar: 0
      minScalar: 0
      maxCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
      minCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
    radial:
      serializedVersion: 2
      minMaxState: 0
      scalar: 0
      minScalar: 0
      maxCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
      minCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
    speedModifier:
      serializedVersion: 2
      minMaxState: 0
      scalar: 1
      minScalar: 1
      maxCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
      minCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
    inWorldSpace: 0
  InheritVelocityModule:
    enabled: 0
    m_Mode: 0
    m_Curve:
      serializedVersion: 2
      minMaxState: 0
      scalar: 0
      minScalar: 0
      maxCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
      minCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
  LifetimeByEmitterSpeedModule:
    enabled: 0
    m_Curve:
      serializedVersion: 2
      minMaxState: 1
      scalar: 1
      minScalar: 1
      maxCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 1
          inSlope: 0
          outSlope: -0.8
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 0.2
          inSlope: -0.8
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
      minCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
    m_Range: {x: 0, y: 1}
  ForceModule:
    enabled: 0
    x:
      serializedVersion: 2
      minMaxState: 0
      scalar: 0
      minScalar: 0
      maxCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
      minCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
    y:
      serializedVersion: 2
      minMaxState: 0
      scalar: 0
      minScalar: 0
      maxCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
      minCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
    z:
      serializedVersion: 2
      minMaxState: 0
      scalar: 0
      minScalar: 0
      maxCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
      minCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
    inWorldSpace: 0
    randomizePerFrame: 0
  ExternalForcesModule:
    serializedVersion: 2
    enabled: 0
    multiplierCurve:
      serializedVersion: 2
      minMaxState: 0
      scalar: 1
      minScalar: 1
      maxCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
      minCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
    influenceFilter: 0
    influenceMask:
      serializedVersion: 2
      m_Bits: 4294967295
    influenceList: []
  ClampVelocityModule:
    enabled: 0
    x:
      serializedVersion: 2
      minMaxState: 0
      scalar: 1
      minScalar: 1
      maxCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
      minCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
    y:
      serializedVersion: 2
      minMaxState: 0
      scalar: 1
      minScalar: 1
      maxCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
      minCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
    z:
      serializedVersion: 2
      minMaxState: 0
      scalar: 1
      minScalar: 1
      maxCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
      minCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
    magnitude:
      serializedVersion: 2
      minMaxState: 0
      scalar: 1
      minScalar: 1
      maxCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
      minCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
    separateAxis: 0
    inWorldSpace: 0
    multiplyDragByParticleSize: 1
    multiplyDragByParticleVelocity: 1
    dampen: 0
    drag:
      serializedVersion: 2
      minMaxState: 0
      scalar: 0
      minScalar: 0
      maxCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
      minCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
  NoiseModule:
    enabled: 0
    strength:
      serializedVersion: 2
      minMaxState: 0
      scalar: 1
      minScalar: 1
      maxCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
      minCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
    strengthY:
      serializedVersion: 2
      minMaxState: 0
      scalar: 1
      minScalar: 1
      maxCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
      minCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
    strengthZ:
      serializedVersion: 2
      minMaxState: 0
      scalar: 1
      minScalar: 1
      maxCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
      minCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
    separateAxes: 0
    frequency: 0.5
    damping: 1
    octaves: 1
    octaveMultiplier: 0.5
    octaveScale: 2
    quality: 1
    scrollSpeed:
      serializedVersion: 2
      minMaxState: 0
      scalar: 0
      minScalar: 0
      maxCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
      minCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
    remap:
      serializedVersion: 2
      minMaxState: 1
      scalar: 1
      minScalar: 1
      maxCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: -1
          inSlope: 0
          outSlope: 2
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 1
          inSlope: 2
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
      minCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
    remapY:
      serializedVersion: 2
      minMaxState: 1
      scalar: 1
      minScalar: 1
      maxCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: -1
          inSlope: 0
          outSlope: 2
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 1
          inSlope: 2
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
      minCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
    remapZ:
      serializedVersion: 2
      minMaxState: 1
      scalar: 1
      minScalar: 1
      maxCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: -1
          inSlope: 0
          outSlope: 2
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 1
          inSlope: 2
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
      minCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
    remapEnabled: 0
    positionAmount:
      serializedVersion: 2
      minMaxState: 0
      scalar: 1
      minScalar: 1
      maxCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
      minCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
    rotationAmount:
      serializedVersion: 2
      minMaxState: 0
      scalar: 0
      minScalar: 0
      maxCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
      minCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
    sizeAmount:
      serializedVersion: 2
      minMaxState: 0
      scalar: 0
      minScalar: 0
      maxCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
      minCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
  SizeBySpeedModule:
    enabled: 0
    curve:
      serializedVersion: 2
      minMaxState: 1
      scalar: 1
      minScalar: 1
      maxCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 0
          inSlope: 0
          outSlope: 1
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 1
          inSlope: 1
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
      minCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
    y:
      serializedVersion: 2
      minMaxState: 1
      scalar: 1
      minScalar: 1
      maxCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 0
          inSlope: 0
          outSlope: 1
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 1
          inSlope: 1
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
      minCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
    z:
      serializedVersion: 2
      minMaxState: 1
      scalar: 1
      minScalar: 1
      maxCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 0
          inSlope: 0
          outSlope: 1
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 1
          inSlope: 1
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
      minCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
    range: {x: 0, y: 1}
    separateAxes: 0
  RotationBySpeedModule:
    enabled: 0
    x:
      serializedVersion: 2
      minMaxState: 0
      scalar: 0
      minScalar: 0
      maxCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
      minCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
    y:
      serializedVersion: 2
      minMaxState: 0
      scalar: 0
      minScalar: 0
      maxCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
      minCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
    curve:
      serializedVersion: 2
      minMaxState: 0
      scalar: 0.7853982
      minScalar: 0.7853982
      maxCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
      minCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
    separateAxes: 0
    range: {x: 0, y: 1}
  ColorBySpeedModule:
    enabled: 0
    gradient:
      serializedVersion: 2
      minMaxState: 1
      minColor: {r: 1, g: 1, b: 1, a: 1}
      maxColor: {r: 1, g: 1, b: 1, a: 1}
      maxGradient:
        serializedVersion: 2
        key0: {r: 1, g: 1, b: 1, a: 1}
        key1: {r: 1, g: 1, b: 1, a: 1}
        key2: {r: 0, g: 0, b: 0, a: 0}
        key3: {r: 0, g: 0, b: 0, a: 0}
        key4: {r: 0, g: 0, b: 0, a: 0}
        key5: {r: 0, g: 0, b: 0, a: 0}
        key6: {r: 0, g: 0, b: 0, a: 0}
        key7: {r: 0, g: 0, b: 0, a: 0}
        ctime0: 0
        ctime1: 65535
        ctime2: 0
        ctime3: 0
        ctime4: 0
        ctime5: 0
        ctime6: 0
        ctime7: 0
        atime0: 0
        atime1: 65535
        atime2: 0
        atime3: 0
        atime4: 0
        atime5: 0
        atime6: 0
        atime7: 0
        m_Mode: 0
        m_ColorSpace: -1
        m_NumColorKeys: 2
        m_NumAlphaKeys: 2
      minGradient:
        serializedVersion: 2
        key0: {r: 1, g: 1, b: 1, a: 1}
        key1: {r: 1, g: 1, b: 1, a: 1}
        key2: {r: 0, g: 0, b: 0, a: 0}
        key3: {r: 0, g: 0, b: 0, a: 0}
        key4: {r: 0, g: 0, b: 0, a: 0}
        key5: {r: 0, g: 0, b: 0, a: 0}
        key6: {r: 0, g: 0, b: 0, a: 0}
        key7: {r: 0, g: 0, b: 0, a: 0}
        ctime0: 0
        ctime1: 65535
        ctime2: 0
        ctime3: 0
        ctime4: 0
        ctime5: 0
        ctime6: 0
        ctime7: 0
        atime0: 0
        atime1: 65535
        atime2: 0
        atime3: 0
        atime4: 0
        atime5: 0
        atime6: 0
        atime7: 0
        m_Mode: 0
        m_ColorSpace: -1
        m_NumColorKeys: 2
        m_NumAlphaKeys: 2
    range: {x: 0, y: 1}
  CollisionModule:
    enabled: 0
    serializedVersion: 4
    type: 0
    collisionMode: 0
    colliderForce: 0
    multiplyColliderForceByParticleSize: 0
    multiplyColliderForceByParticleSpeed: 0
    multiplyColliderForceByCollisionAngle: 1
    m_Planes: []
    m_Dampen:
      serializedVersion: 2
      minMaxState: 0
      scalar: 0
      minScalar: 0
      maxCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
      minCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
    m_Bounce:
      serializedVersion: 2
      minMaxState: 0
      scalar: 1
      minScalar: 1
      maxCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
      minCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
    m_EnergyLossOnCollision:
      serializedVersion: 2
      minMaxState: 0
      scalar: 0
      minScalar: 0
      maxCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
      minCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
    minKillSpeed: 0
    maxKillSpeed: 10000
    radiusScale: 1
    collidesWith:
      serializedVersion: 2
      m_Bits: 4294967295
    maxCollisionShapes: 256
    quality: 0
    voxelSize: 0.5
    collisionMessages: 0
    collidesWithDynamic: 1
    interiorCollisions: 0
  TriggerModule:
    enabled: 0
    serializedVersion: 2
    inside: 1
    outside: 0
    enter: 0
    exit: 0
    colliderQueryMode: 0
    radiusScale: 1
    primitives: []
  SubModule:
    serializedVersion: 2
    enabled: 0
    subEmitters:
    - serializedVersion: 3
      emitter: {fileID: 0}
      type: 0
      properties: 0
      emitProbability: 1
  LightsModule:
    enabled: 0
    ratio: 0
    light: {fileID: 0}
    randomDistribution: 1
    color: 1
    range: 1
    intensity: 1
    rangeCurve:
      serializedVersion: 2
      minMaxState: 0
      scalar: 1
      minScalar: 1
      maxCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
      minCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
    intensityCurve:
      serializedVersion: 2
      minMaxState: 0
      scalar: 1
      minScalar: 1
      maxCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
      minCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
    maxLights: 20
  TrailModule:
    enabled: 0
    mode: 0
    ratio: 1
    lifetime:
      serializedVersion: 2
      minMaxState: 0
      scalar: 1
      minScalar: 1
      maxCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
      minCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
    minVertexDistance: 0.2
    textureMode: 0
    textureScale: {x: 1, y: 1}
    ribbonCount: 1
    shadowBias: 0.5
    worldSpace: 0
    dieWithParticles: 1
    sizeAffectsWidth: 1
    sizeAffectsLifetime: 0
    inheritParticleColor: 1
    generateLightingData: 0
    splitSubEmitterRibbons: 0
    attachRibbonsToTransform: 0
    colorOverLifetime:
      serializedVersion: 2
      minMaxState: 0
      minColor: {r: 1, g: 1, b: 1, a: 1}
      maxColor: {r: 1, g: 1, b: 1, a: 1}
      maxGradient:
        serializedVersion: 2
        key0: {r: 1, g: 1, b: 1, a: 1}
        key1: {r: 1, g: 1, b: 1, a: 1}
        key2: {r: 0, g: 0, b: 0, a: 0}
        key3: {r: 0, g: 0, b: 0, a: 0}
        key4: {r: 0, g: 0, b: 0, a: 0}
        key5: {r: 0, g: 0, b: 0, a: 0}
        key6: {r: 0, g: 0, b: 0, a: 0}
        key7: {r: 0, g: 0, b: 0, a: 0}
        ctime0: 0
        ctime1: 65535
        ctime2: 0
        ctime3: 0
        ctime4: 0
        ctime5: 0
        ctime6: 0
        ctime7: 0
        atime0: 0
        atime1: 65535
        atime2: 0
        atime3: 0
        atime4: 0
        atime5: 0
        atime6: 0
        atime7: 0
        m_Mode: 0
        m_ColorSpace: -1
        m_NumColorKeys: 2
        m_NumAlphaKeys: 2
      minGradient:
        serializedVersion: 2
        key0: {r: 1, g: 1, b: 1, a: 1}
        key1: {r: 1, g: 1, b: 1, a: 1}
        key2: {r: 0, g: 0, b: 0, a: 0}
        key3: {r: 0, g: 0, b: 0, a: 0}
        key4: {r: 0, g: 0, b: 0, a: 0}
        key5: {r: 0, g: 0, b: 0, a: 0}
        key6: {r: 0, g: 0, b: 0, a: 0}
        key7: {r: 0, g: 0, b: 0, a: 0}
        ctime0: 0
        ctime1: 65535
        ctime2: 0
        ctime3: 0
        ctime4: 0
        ctime5: 0
        ctime6: 0
        ctime7: 0
        atime0: 0
        atime1: 65535
        atime2: 0
        atime3: 0
        atime4: 0
        atime5: 0
        atime6: 0
        atime7: 0
        m_Mode: 0
        m_ColorSpace: -1
        m_NumColorKeys: 2
        m_NumAlphaKeys: 2
    widthOverTrail:
      serializedVersion: 2
      minMaxState: 0
      scalar: 1
      minScalar: 1
      maxCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
      minCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
    colorOverTrail:
      serializedVersion: 2
      minMaxState: 0
      minColor: {r: 1, g: 1, b: 1, a: 1}
      maxColor: {r: 1, g: 1, b: 1, a: 1}
      maxGradient:
        serializedVersion: 2
        key0: {r: 1, g: 1, b: 1, a: 1}
        key1: {r: 1, g: 1, b: 1, a: 1}
        key2: {r: 0, g: 0, b: 0, a: 0}
        key3: {r: 0, g: 0, b: 0, a: 0}
        key4: {r: 0, g: 0, b: 0, a: 0}
        key5: {r: 0, g: 0, b: 0, a: 0}
        key6: {r: 0, g: 0, b: 0, a: 0}
        key7: {r: 0, g: 0, b: 0, a: 0}
        ctime0: 0
        ctime1: 65535
        ctime2: 0
        ctime3: 0
        ctime4: 0
        ctime5: 0
        ctime6: 0
        ctime7: 0
        atime0: 0
        atime1: 65535
        atime2: 0
        atime3: 0
        atime4: 0
        atime5: 0
        atime6: 0
        atime7: 0
        m_Mode: 0
        m_ColorSpace: -1
        m_NumColorKeys: 2
        m_NumAlphaKeys: 2
      minGradient:
        serializedVersion: 2
        key0: {r: 1, g: 1, b: 1, a: 1}
        key1: {r: 1, g: 1, b: 1, a: 1}
        key2: {r: 0, g: 0, b: 0, a: 0}
        key3: {r: 0, g: 0, b: 0, a: 0}
        key4: {r: 0, g: 0, b: 0, a: 0}
        key5: {r: 0, g: 0, b: 0, a: 0}
        key6: {r: 0, g: 0, b: 0, a: 0}
        key7: {r: 0, g: 0, b: 0, a: 0}
        ctime0: 0
        ctime1: 65535
        ctime2: 0
        ctime3: 0
        ctime4: 0
        ctime5: 0
        ctime6: 0
        ctime7: 0
        atime0: 0
        atime1: 65535
        atime2: 0
        atime3: 0
        atime4: 0
        atime5: 0
        atime6: 0
        atime7: 0
        m_Mode: 0
        m_ColorSpace: -1
        m_NumColorKeys: 2
        m_NumAlphaKeys: 2
  CustomDataModule:
    enabled: 0
    mode0: 0
    vectorComponentCount0: 4
    color0:
      serializedVersion: 2
      minMaxState: 0
      minColor: {r: 1, g: 1, b: 1, a: 1}
      maxColor: {r: 1, g: 1, b: 1, a: 1}
      maxGradient:
        serializedVersion: 2
        key0: {r: 1, g: 1, b: 1, a: 1}
        key1: {r: 1, g: 1, b: 1, a: 1}
        key2: {r: 0, g: 0, b: 0, a: 0}
        key3: {r: 0, g: 0, b: 0, a: 0}
        key4: {r: 0, g: 0, b: 0, a: 0}
        key5: {r: 0, g: 0, b: 0, a: 0}
        key6: {r: 0, g: 0, b: 0, a: 0}
        key7: {r: 0, g: 0, b: 0, a: 0}
        ctime0: 0
        ctime1: 65535
        ctime2: 0
        ctime3: 0
        ctime4: 0
        ctime5: 0
        ctime6: 0
        ctime7: 0
        atime0: 0
        atime1: 65535
        atime2: 0
        atime3: 0
        atime4: 0
        atime5: 0
        atime6: 0
        atime7: 0
        m_Mode: 0
        m_ColorSpace: -1
        m_NumColorKeys: 2
        m_NumAlphaKeys: 2
      minGradient:
        serializedVersion: 2
        key0: {r: 1, g: 1, b: 1, a: 1}
        key1: {r: 1, g: 1, b: 1, a: 1}
        key2: {r: 0, g: 0, b: 0, a: 0}
        key3: {r: 0, g: 0, b: 0, a: 0}
        key4: {r: 0, g: 0, b: 0, a: 0}
        key5: {r: 0, g: 0, b: 0, a: 0}
        key6: {r: 0, g: 0, b: 0, a: 0}
        key7: {r: 0, g: 0, b: 0, a: 0}
        ctime0: 0
        ctime1: 65535
        ctime2: 0
        ctime3: 0
        ctime4: 0
        ctime5: 0
        ctime6: 0
        ctime7: 0
        atime0: 0
        atime1: 65535
        atime2: 0
        atime3: 0
        atime4: 0
        atime5: 0
        atime6: 0
        atime7: 0
        m_Mode: 0
        m_ColorSpace: -1
        m_NumColorKeys: 2
        m_NumAlphaKeys: 2
    colorLabel0: Color
    vector0_0:
      serializedVersion: 2
      minMaxState: 0
      scalar: 0
      minScalar: 0
      maxCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
      minCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
    vectorLabel0_0: X
    vector0_1:
      serializedVersion: 2
      minMaxState: 0
      scalar: 0
      minScalar: 0
      maxCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
      minCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
    vectorLabel0_1: Y
    vector0_2:
      serializedVersion: 2
      minMaxState: 0
      scalar: 0
      minScalar: 0
      maxCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
      minCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
    vectorLabel0_2: Z
    vector0_3:
      serializedVersion: 2
      minMaxState: 0
      scalar: 0
      minScalar: 0
      maxCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
      minCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
    vectorLabel0_3: W
    mode1: 0
    vectorComponentCount1: 4
    color1:
      serializedVersion: 2
      minMaxState: 0
      minColor: {r: 1, g: 1, b: 1, a: 1}
      maxColor: {r: 1, g: 1, b: 1, a: 1}
      maxGradient:
        serializedVersion: 2
        key0: {r: 1, g: 1, b: 1, a: 1}
        key1: {r: 1, g: 1, b: 1, a: 1}
        key2: {r: 0, g: 0, b: 0, a: 0}
        key3: {r: 0, g: 0, b: 0, a: 0}
        key4: {r: 0, g: 0, b: 0, a: 0}
        key5: {r: 0, g: 0, b: 0, a: 0}
        key6: {r: 0, g: 0, b: 0, a: 0}
        key7: {r: 0, g: 0, b: 0, a: 0}
        ctime0: 0
        ctime1: 65535
        ctime2: 0
        ctime3: 0
        ctime4: 0
        ctime5: 0
        ctime6: 0
        ctime7: 0
        atime0: 0
        atime1: 65535
        atime2: 0
        atime3: 0
        atime4: 0
        atime5: 0
        atime6: 0
        atime7: 0
        m_Mode: 0
        m_ColorSpace: -1
        m_NumColorKeys: 2
        m_NumAlphaKeys: 2
      minGradient:
        serializedVersion: 2
        key0: {r: 1, g: 1, b: 1, a: 1}
        key1: {r: 1, g: 1, b: 1, a: 1}
        key2: {r: 0, g: 0, b: 0, a: 0}
        key3: {r: 0, g: 0, b: 0, a: 0}
        key4: {r: 0, g: 0, b: 0, a: 0}
        key5: {r: 0, g: 0, b: 0, a: 0}
        key6: {r: 0, g: 0, b: 0, a: 0}
        key7: {r: 0, g: 0, b: 0, a: 0}
        ctime0: 0
        ctime1: 65535
        ctime2: 0
        ctime3: 0
        ctime4: 0
        ctime5: 0
        ctime6: 0
        ctime7: 0
        atime0: 0
        atime1: 65535
        atime2: 0
        atime3: 0
        atime4: 0
        atime5: 0
        atime6: 0
        atime7: 0
        m_Mode: 0
        m_ColorSpace: -1
        m_NumColorKeys: 2
        m_NumAlphaKeys: 2
    colorLabel1: Color
    vector1_0:
      serializedVersion: 2
      minMaxState: 0
      scalar: 0
      minScalar: 0
      maxCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
      minCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
    vectorLabel1_0: X
    vector1_1:
      serializedVersion: 2
      minMaxState: 0
      scalar: 0
      minScalar: 0
      maxCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
      minCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
    vectorLabel1_1: Y
    vector1_2:
      serializedVersion: 2
      minMaxState: 0
      scalar: 0
      minScalar: 0
      maxCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
      minCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
    vectorLabel1_2: Z
    vector1_3:
      serializedVersion: 2
      minMaxState: 0
      scalar: 0
      minScalar: 0
      maxCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
      minCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
    vectorLabel1_3: W
--- !u!4 &529940564
Transform:
  m_ObjectHideFlags: 0
  m_CorrespondingSourceObject: {fileID: 0}
  m_PrefabInstance: {fileID: 0}
  m_PrefabAsset: {fileID: 0}
  m_GameObject: {fileID: 529940561}
  serializedVersion: 2
  m_LocalRotation: {x: -0.52407336, y: -0.13719898, z: 0.26993656, w: 0.7960263}
  m_LocalPosition: {x: -56.56, y: 85.48, z: 10.37}
  m_LocalScale: {x: 1, y: 1, z: 1}
  m_ConstrainProportionsScale: 0
  m_Children: []
  m_Father: {fileID: 0}
  m_LocalEulerAnglesHint: {x: -130.511, y: 129.483, z: -118}
--- !u!1001 &561899151
PrefabInstance:
  m_ObjectHideFlags: 0
  serializedVersion: 2
  m_Modification:
    serializedVersion: 3
    m_TransformParent: {fileID: 0}
    m_Modifications:
    - target: {fileID: -8679921383154817045, guid: 68de8feddf9657a409f21e3eea01b124, type: 3}
      propertyPath: m_LocalScale.x
      value: 0.5
      objectReference: {fileID: 0}
    - target: {fileID: -8679921383154817045, guid: 68de8feddf9657a409f21e3eea01b124, type: 3}
      propertyPath: m_LocalScale.y
      value: 0.5
      objectReference: {fileID: 0}
    - target: {fileID: -8679921383154817045, guid: 68de8feddf9657a409f21e3eea01b124, type: 3}
      propertyPath: m_LocalScale.z
      value: 0.5
      objectReference: {fileID: 0}
    - target: {fileID: -8679921383154817045, guid: 68de8feddf9657a409f21e3eea01b124, type: 3}
      propertyPath: m_LocalPosition.x
      value: 9.185764
      objectReference: {fileID: 0}
    - target: {fileID: -8679921383154817045, guid: 68de8feddf9657a409f21e3eea01b124, type: 3}
      propertyPath: m_LocalPosition.y
      value: 0
      objectReference: {fileID: 0}
    - target: {fileID: -8679921383154817045, guid: 68de8feddf9657a409f21e3eea01b124, type: 3}
      propertyPath: m_LocalPosition.z
      value: 1.0868378
      objectReference: {fileID: 0}
    - target: {fileID: -8679921383154817045, guid: 68de8feddf9657a409f21e3eea01b124, type: 3}
      propertyPath: m_LocalRotation.w
      value: 1
      objectReference: {fileID: 0}
    - target: {fileID: -8679921383154817045, guid: 68de8feddf9657a409f21e3eea01b124, type: 3}
      propertyPath: m_LocalRotation.x
      value: 0
      objectReference: {fileID: 0}
    - target: {fileID: -8679921383154817045, guid: 68de8feddf9657a409f21e3eea01b124, type: 3}
      propertyPath: m_LocalRotation.y
      value: 0
      objectReference: {fileID: 0}
    - target: {fileID: -8679921383154817045, guid: 68de8feddf9657a409f21e3eea01b124, type: 3}
      propertyPath: m_LocalRotation.z
      value: 0
      objectReference: {fileID: 0}
    - target: {fileID: -8679921383154817045, guid: 68de8feddf9657a409f21e3eea01b124, type: 3}
      propertyPath: m_LocalEulerAnglesHint.x
      value: 0
      objectReference: {fileID: 0}
    - target: {fileID: -8679921383154817045, guid: 68de8feddf9657a409f21e3eea01b124, type: 3}
      propertyPath: m_LocalEulerAnglesHint.y
      value: 0
      objectReference: {fileID: 0}
    - target: {fileID: -8679921383154817045, guid: 68de8feddf9657a409f21e3eea01b124, type: 3}
      propertyPath: m_LocalEulerAnglesHint.z
      value: 0
      objectReference: {fileID: 0}
    - target: {fileID: -7918335002988649766, guid: 68de8feddf9657a409f21e3eea01b124, type: 3}
      propertyPath: m_Materials.Array.data[0]
      value: 
      objectReference: {fileID: 2100000, guid: c733e8a7b5a7be84781239f1eb92dd57, type: 2}
    - target: {fileID: -2571118854743697038, guid: 68de8feddf9657a409f21e3eea01b124, type: 3}
      propertyPath: m_Materials.Array.data[0]
      value: 
      objectReference: {fileID: 2100000, guid: c733e8a7b5a7be84781239f1eb92dd57, type: 2}
    - target: {fileID: -1439730007547781893, guid: 68de8feddf9657a409f21e3eea01b124, type: 3}
      propertyPath: m_Materials.Array.data[0]
      value: 
      objectReference: {fileID: 2100000, guid: c733e8a7b5a7be84781239f1eb92dd57, type: 2}
    - target: {fileID: 919132149155446097, guid: 68de8feddf9657a409f21e3eea01b124, type: 3}
      propertyPath: m_Name
      value: Enviroment
      objectReference: {fileID: 0}
    - target: {fileID: 7071182760956848314, guid: 68de8feddf9657a409f21e3eea01b124, type: 3}
      propertyPath: m_Materials.Array.data[0]
      value: 
      objectReference: {fileID: 2100000, guid: c733e8a7b5a7be84781239f1eb92dd57, type: 2}
    - target: {fileID: 7202271454713460447, guid: 68de8feddf9657a409f21e3eea01b124, type: 3}
      propertyPath: m_Materials.Array.data[0]
      value: 
      objectReference: {fileID: 2100000, guid: c733e8a7b5a7be84781239f1eb92dd57, type: 2}
    m_RemovedComponents: []
    m_RemovedGameObjects: []
    m_AddedGameObjects: []
    m_AddedComponents: []
  m_SourcePrefab: {fileID: 100100000, guid: 68de8feddf9657a409f21e3eea01b124, type: 3}
--- !u!1 &705507993
GameObject:
  m_ObjectHideFlags: 0
  m_CorrespondingSourceObject: {fileID: 0}
  m_PrefabInstance: {fileID: 0}
  m_PrefabAsset: {fileID: 0}
  serializedVersion: 6
  m_Component:
  - component: {fileID: 705507995}
  - component: {fileID: 705507994}
  m_Layer: 0
  m_Name: Directional Light
  m_TagString: Untagged
  m_Icon: {fileID: 0}
  m_NavMeshLayer: 0
  m_StaticEditorFlags: 0
  m_IsActive: 1
--- !u!108 &705507994
Light:
  m_ObjectHideFlags: 0
  m_CorrespondingSourceObject: {fileID: 0}
  m_PrefabInstance: {fileID: 0}
  m_PrefabAsset: {fileID: 0}
  m_GameObject: {fileID: 705507993}
  m_Enabled: 1
  serializedVersion: 10
  m_Type: 1
  m_Shape: 0
  m_Color: {r: 1, g: 0.6699237, b: 0.34591186, a: 1}
  m_Intensity: 1
  m_Range: 10
  m_SpotAngle: 30
  m_InnerSpotAngle: 21.80208
  m_CookieSize: 10
  m_Shadows:
    m_Type: 2
    m_Resolution: -1
    m_CustomResolution: -1
    m_Strength: 1
    m_Bias: 0.05
    m_NormalBias: 0.4
    m_NearPlane: 0.2
    m_CullingMatrixOverride:
      e00: 1
      e01: 0
      e02: 0
      e03: 0
      e10: 0
      e11: 1
      e12: 0
      e13: 0
      e20: 0
      e21: 0
      e22: 1
      e23: 0
      e30: 0
      e31: 0
      e32: 0
      e33: 1
    m_UseCullingMatrixOverride: 0
  m_Cookie: {fileID: 0}
  m_DrawHalo: 0
  m_Flare: {fileID: 0}
  m_RenderMode: 0
  m_CullingMask:
    serializedVersion: 2
    m_Bits: 4294967295
  m_RenderingLayerMask: 1
  m_Lightmapping: 1
  m_LightShadowCasterMode: 0
  m_AreaSize: {x: 1, y: 1}
  m_BounceIntensity: 1
  m_ColorTemperature: 6570
  m_UseColorTemperature: 0
  m_BoundingSphereOverride: {x: 0, y: 0, z: 0, w: 0}
  m_UseBoundingSphereOverride: 0
  m_UseViewFrustumForShadowCasterCull: 1
  m_ShadowRadius: 0
  m_ShadowAngle: 0
--- !u!4 &705507995
Transform:
  m_ObjectHideFlags: 0
  m_CorrespondingSourceObject: {fileID: 0}
  m_PrefabInstance: {fileID: 0}
  m_PrefabAsset: {fileID: 0}
  m_GameObject: {fileID: 705507993}
  serializedVersion: 2
  m_LocalRotation: {x: 0.40821788, y: -0.23456968, z: 0.10938163, w: 0.8754261}
  m_LocalPosition: {x: 0, y: 3, z: 0}
  m_LocalScale: {x: 1, y: 1, z: 1}
  m_ConstrainProportionsScale: 0
  m_Children: []
  m_Father: {fileID: 0}
  m_LocalEulerAnglesHint: {x: 50, y: -30, z: 0}
--- !u!1 &842288764
GameObject:
  m_ObjectHideFlags: 0
  m_CorrespondingSourceObject: {fileID: 0}
  m_PrefabInstance: {fileID: 0}
  m_PrefabAsset: {fileID: 0}
  serializedVersion: 6
  m_Component:
  - component: {fileID: 842288767}
  - component: {fileID: 842288766}
  - component: {fileID: 842288765}
  m_Layer: 0
  m_Name: Particle System (1)
  m_TagString: Untagged
  m_Icon: {fileID: 0}
  m_NavMeshLayer: 0
  m_StaticEditorFlags: 0
  m_IsActive: 1
--- !u!199 &842288765
ParticleSystemRenderer:
  serializedVersion: 6
  m_ObjectHideFlags: 0
  m_CorrespondingSourceObject: {fileID: 0}
  m_PrefabInstance: {fileID: 0}
  m_PrefabAsset: {fileID: 0}
  m_GameObject: {fileID: 842288764}
  m_Enabled: 1
  m_CastShadows: 0
  m_ReceiveShadows: 0
  m_DynamicOccludee: 1
  m_StaticShadowCaster: 0
  m_MotionVectors: 1
  m_LightProbeUsage: 0
  m_ReflectionProbeUsage: 0
  m_RayTracingMode: 0
  m_RayTraceProcedural: 0
  m_RenderingLayerMask: 1
  m_RendererPriority: 0
  m_Materials:
  - {fileID: 10308, guid: 0000000000000000f000000000000000, type: 0}
  m_StaticBatchInfo:
    firstSubMesh: 0
    subMeshCount: 0
  m_StaticBatchRoot: {fileID: 0}
  m_ProbeAnchor: {fileID: 0}
  m_LightProbeVolumeOverride: {fileID: 0}
  m_ScaleInLightmap: 1
  m_ReceiveGI: 1
  m_PreserveUVs: 0
  m_IgnoreNormalsForChartDetection: 0
  m_ImportantGI: 0
  m_StitchLightmapSeams: 1
  m_SelectedEditorRenderState: 3
  m_MinimumChartSize: 4
  m_AutoUVMaxDistance: 0.5
  m_AutoUVMaxAngle: 89
  m_LightmapParameters: {fileID: 0}
  m_SortingLayerID: 0
  m_SortingLayer: 0
  m_SortingOrder: 0
  m_RenderMode: 0
  m_MeshDistribution: 0
  m_SortMode: 0
  m_MinParticleSize: 0
  m_MaxParticleSize: 0.5
  m_CameraVelocityScale: 0
  m_VelocityScale: 0
  m_LengthScale: 2
  m_SortingFudge: 0
  m_NormalDirection: 1
  m_ShadowBias: 0
  m_RenderAlignment: 0
  m_Pivot: {x: 0, y: 0, z: 0}
  m_Flip: {x: 0, y: 0, z: 0}
  m_UseCustomVertexStreams: 0
  m_EnableGPUInstancing: 1
  m_ApplyActiveColorSpace: 1
  m_AllowRoll: 1
  m_FreeformStretching: 0
  m_RotateWithStretchDirection: 1
  m_VertexStreams: 00010304
  m_Mesh: {fileID: 0}
  m_Mesh1: {fileID: 0}
  m_Mesh2: {fileID: 0}
  m_Mesh3: {fileID: 0}
  m_MeshWeighting: 1
  m_MeshWeighting1: 1
  m_MeshWeighting2: 1
  m_MeshWeighting3: 1
  m_MaskInteraction: 0
--- !u!198 &842288766
ParticleSystem:
  m_ObjectHideFlags: 0
  m_CorrespondingSourceObject: {fileID: 0}
  m_PrefabInstance: {fileID: 0}
  m_PrefabAsset: {fileID: 0}
  m_GameObject: {fileID: 842288764}
  serializedVersion: 8
  lengthInSec: 5
  simulationSpeed: 1
  stopAction: 0
  cullingMode: 0
  ringBufferMode: 0
  ringBufferLoopRange: {x: 0, y: 1}
  emitterVelocityMode: 1
  looping: 1
  prewarm: 0
  playOnAwake: 1
  useUnscaledTime: 0
  autoRandomSeed: 1
  startDelay:
    serializedVersion: 2
    minMaxState: 0
    scalar: 0
    minScalar: 0
    maxCurve:
      serializedVersion: 2
      m_Curve:
      - serializedVersion: 3
        time: 0
        value: 0
        inSlope: 0
        outSlope: 0
        tangentMode: 0
        weightedMode: 0
        inWeight: 0.33333334
        outWeight: 0.33333334
      - serializedVersion: 3
        time: 1
        value: 0
        inSlope: 0
        outSlope: 0
        tangentMode: 0
        weightedMode: 0
        inWeight: 0.33333334
        outWeight: 0.33333334
      m_PreInfinity: 2
      m_PostInfinity: 2
      m_RotationOrder: 4
    minCurve:
      serializedVersion: 2
      m_Curve:
      - serializedVersion: 3
        time: 0
        value: 0
        inSlope: 0
        outSlope: 0
        tangentMode: 0
        weightedMode: 0
        inWeight: 0.33333334
        outWeight: 0.33333334
      - serializedVersion: 3
        time: 1
        value: 0
        inSlope: 0
        outSlope: 0
        tangentMode: 0
        weightedMode: 0
        inWeight: 0.33333334
        outWeight: 0.33333334
      m_PreInfinity: 2
      m_PostInfinity: 2
      m_RotationOrder: 4
  moveWithTransform: 0
  moveWithCustomTransform: {fileID: 0}
  scalingMode: 1
  randomSeed: 0
  InitialModule:
    serializedVersion: 3
    enabled: 1
    startLifetime:
      serializedVersion: 2
      minMaxState: 0
      scalar: 5
      minScalar: 5
      maxCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
      minCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
    startSpeed:
      serializedVersion: 2
      minMaxState: 0
      scalar: 5
      minScalar: 5
      maxCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
      minCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
    startColor:
      serializedVersion: 2
      minMaxState: 0
      minColor: {r: 1, g: 1, b: 1, a: 1}
      maxColor: {r: 1, g: 0.5061273, b: 0, a: 1}
      maxGradient:
        serializedVersion: 2
        key0: {r: 1, g: 1, b: 1, a: 1}
        key1: {r: 1, g: 1, b: 1, a: 1}
        key2: {r: 0, g: 0, b: 0, a: 0}
        key3: {r: 0, g: 0, b: 0, a: 0}
        key4: {r: 0, g: 0, b: 0, a: 0}
        key5: {r: 0, g: 0, b: 0, a: 0}
        key6: {r: 0, g: 0, b: 0, a: 0}
        key7: {r: 0, g: 0, b: 0, a: 0}
        ctime0: 0
        ctime1: 65535
        ctime2: 0
        ctime3: 0
        ctime4: 0
        ctime5: 0
        ctime6: 0
        ctime7: 0
        atime0: 0
        atime1: 65535
        atime2: 0
        atime3: 0
        atime4: 0
        atime5: 0
        atime6: 0
        atime7: 0
        m_Mode: 0
        m_ColorSpace: -1
        m_NumColorKeys: 2
        m_NumAlphaKeys: 2
      minGradient:
        serializedVersion: 2
        key0: {r: 1, g: 1, b: 1, a: 1}
        key1: {r: 1, g: 1, b: 1, a: 1}
        key2: {r: 0, g: 0, b: 0, a: 0}
        key3: {r: 0, g: 0, b: 0, a: 0}
        key4: {r: 0, g: 0, b: 0, a: 0}
        key5: {r: 0, g: 0, b: 0, a: 0}
        key6: {r: 0, g: 0, b: 0, a: 0}
        key7: {r: 0, g: 0, b: 0, a: 0}
        ctime0: 0
        ctime1: 65535
        ctime2: 0
        ctime3: 0
        ctime4: 0
        ctime5: 0
        ctime6: 0
        ctime7: 0
        atime0: 0
        atime1: 65535
        atime2: 0
        atime3: 0
        atime4: 0
        atime5: 0
        atime6: 0
        atime7: 0
        m_Mode: 0
        m_ColorSpace: -1
        m_NumColorKeys: 2
        m_NumAlphaKeys: 2
    startSize:
      serializedVersion: 2
      minMaxState: 0
      scalar: 1
      minScalar: 1
      maxCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
      minCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
    startSizeY:
      serializedVersion: 2
      minMaxState: 0
      scalar: 1
      minScalar: 1
      maxCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
      minCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
    startSizeZ:
      serializedVersion: 2
      minMaxState: 0
      scalar: 1
      minScalar: 1
      maxCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
      minCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
    startRotationX:
      serializedVersion: 2
      minMaxState: 0
      scalar: 0
      minScalar: 0
      maxCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
      minCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
    startRotationY:
      serializedVersion: 2
      minMaxState: 0
      scalar: 0
      minScalar: 0
      maxCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
      minCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
    startRotation:
      serializedVersion: 2
      minMaxState: 0
      scalar: 0
      minScalar: 0
      maxCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
      minCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
    randomizeRotationDirection: 0
    gravitySource: 0
    maxNumParticles: 1000
    customEmitterVelocity: {x: 0, y: 0, z: 0}
    size3D: 0
    rotation3D: 0
    gravityModifier:
      serializedVersion: 2
      minMaxState: 0
      scalar: 0
      minScalar: 0
      maxCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
      minCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
  ShapeModule:
    serializedVersion: 6
    enabled: 1
    type: 4
    angle: 25
    length: 5
    boxThickness: {x: 0, y: 0, z: 0}
    radiusThickness: 1
    donutRadius: 0.2
    m_Position: {x: 0, y: 0, z: 0}
    m_Rotation: {x: 0, y: 0, z: 0}
    m_Scale: {x: 1, y: 1, z: 1}
    placementMode: 0
    m_MeshMaterialIndex: 0
    m_MeshNormalOffset: 0
    m_MeshSpawn:
      mode: 0
      spread: 0
      speed:
        serializedVersion: 2
        minMaxState: 0
        scalar: 1
        minScalar: 1
        maxCurve:
          serializedVersion: 2
          m_Curve:
          - serializedVersion: 3
            time: 0
            value: 1
            inSlope: 0
            outSlope: 0
            tangentMode: 0
            weightedMode: 0
            inWeight: 0.33333334
            outWeight: 0.33333334
          - serializedVersion: 3
            time: 1
            value: 1
            inSlope: 0
            outSlope: 0
            tangentMode: 0
            weightedMode: 0
            inWeight: 0.33333334
            outWeight: 0.33333334
          m_PreInfinity: 2
          m_PostInfinity: 2
          m_RotationOrder: 4
        minCurve:
          serializedVersion: 2
          m_Curve:
          - serializedVersion: 3
            time: 0
            value: 1
            inSlope: 0
            outSlope: 0
            tangentMode: 0
            weightedMode: 0
            inWeight: 0.33333334
            outWeight: 0.33333334
          - serializedVersion: 3
            time: 1
            value: 1
            inSlope: 0
            outSlope: 0
            tangentMode: 0
            weightedMode: 0
            inWeight: 0.33333334
            outWeight: 0.33333334
          m_PreInfinity: 2
          m_PostInfinity: 2
          m_RotationOrder: 4
    m_Mesh: {fileID: 0}
    m_MeshRenderer: {fileID: 0}
    m_SkinnedMeshRenderer: {fileID: 0}
    m_Sprite: {fileID: 0}
    m_SpriteRenderer: {fileID: 0}
    m_UseMeshMaterialIndex: 0
    m_UseMeshColors: 1
    alignToDirection: 0
    m_Texture: {fileID: 0}
    m_TextureClipChannel: 3
    m_TextureClipThreshold: 0
    m_TextureUVChannel: 0
    m_TextureColorAffectsParticles: 1
    m_TextureAlphaAffectsParticles: 1
    m_TextureBilinearFiltering: 0
    randomDirectionAmount: 0
    sphericalDirectionAmount: 0
    randomPositionAmount: 0
    radius:
      value: 1
      mode: 0
      spread: 0
      speed:
        serializedVersion: 2
        minMaxState: 0
        scalar: 1
        minScalar: 1
        maxCurve:
          serializedVersion: 2
          m_Curve:
          - serializedVersion: 3
            time: 0
            value: 1
            inSlope: 0
            outSlope: 0
            tangentMode: 0
            weightedMode: 0
            inWeight: 0.33333334
            outWeight: 0.33333334
          - serializedVersion: 3
            time: 1
            value: 1
            inSlope: 0
            outSlope: 0
            tangentMode: 0
            weightedMode: 0
            inWeight: 0.33333334
            outWeight: 0.33333334
          m_PreInfinity: 2
          m_PostInfinity: 2
          m_RotationOrder: 4
        minCurve:
          serializedVersion: 2
          m_Curve:
          - serializedVersion: 3
            time: 0
            value: 1
            inSlope: 0
            outSlope: 0
            tangentMode: 0
            weightedMode: 0
            inWeight: 0.33333334
            outWeight: 0.33333334
          - serializedVersion: 3
            time: 1
            value: 1
            inSlope: 0
            outSlope: 0
            tangentMode: 0
            weightedMode: 0
            inWeight: 0.33333334
            outWeight: 0.33333334
          m_PreInfinity: 2
          m_PostInfinity: 2
          m_RotationOrder: 4
    arc:
      value: 360
      mode: 0
      spread: 0
      speed:
        serializedVersion: 2
        minMaxState: 0
        scalar: 1
        minScalar: 1
        maxCurve:
          serializedVersion: 2
          m_Curve:
          - serializedVersion: 3
            time: 0
            value: 1
            inSlope: 0
            outSlope: 0
            tangentMode: 0
            weightedMode: 0
            inWeight: 0.33333334
            outWeight: 0.33333334
          - serializedVersion: 3
            time: 1
            value: 1
            inSlope: 0
            outSlope: 0
            tangentMode: 0
            weightedMode: 0
            inWeight: 0.33333334
            outWeight: 0.33333334
          m_PreInfinity: 2
          m_PostInfinity: 2
          m_RotationOrder: 4
        minCurve:
          serializedVersion: 2
          m_Curve:
          - serializedVersion: 3
            time: 0
            value: 1
            inSlope: 0
            outSlope: 0
            tangentMode: 0
            weightedMode: 0
            inWeight: 0.33333334
            outWeight: 0.33333334
          - serializedVersion: 3
            time: 1
            value: 1
            inSlope: 0
            outSlope: 0
            tangentMode: 0
            weightedMode: 0
            inWeight: 0.33333334
            outWeight: 0.33333334
          m_PreInfinity: 2
          m_PostInfinity: 2
          m_RotationOrder: 4
  EmissionModule:
    enabled: 1
    serializedVersion: 4
    rateOverTime:
      serializedVersion: 2
      minMaxState: 0
      scalar: 10
      minScalar: 10
      maxCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
      minCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
    rateOverDistance:
      serializedVersion: 2
      minMaxState: 0
      scalar: 0
      minScalar: 0
      maxCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
      minCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
    m_BurstCount: 0
    m_Bursts: []
  SizeModule:
    enabled: 0
    curve:
      serializedVersion: 2
      minMaxState: 1
      scalar: 1
      minScalar: 1
      maxCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 0
          inSlope: 0
          outSlope: 1
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 1
          inSlope: 1
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
      minCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
    y:
      serializedVersion: 2
      minMaxState: 1
      scalar: 1
      minScalar: 1
      maxCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 0
          inSlope: 0
          outSlope: 1
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 1
          inSlope: 1
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
      minCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
    z:
      serializedVersion: 2
      minMaxState: 1
      scalar: 1
      minScalar: 1
      maxCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 0
          inSlope: 0
          outSlope: 1
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 1
          inSlope: 1
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
      minCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
    separateAxes: 0
  RotationModule:
    enabled: 0
    x:
      serializedVersion: 2
      minMaxState: 0
      scalar: 0
      minScalar: 0
      maxCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
      minCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
    y:
      serializedVersion: 2
      minMaxState: 0
      scalar: 0
      minScalar: 0
      maxCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
      minCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
    curve:
      serializedVersion: 2
      minMaxState: 0
      scalar: 0.7853982
      minScalar: 0.7853982
      maxCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
      minCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
    separateAxes: 0
  ColorModule:
    enabled: 0
    gradient:
      serializedVersion: 2
      minMaxState: 1
      minColor: {r: 1, g: 1, b: 1, a: 1}
      maxColor: {r: 1, g: 1, b: 1, a: 1}
      maxGradient:
        serializedVersion: 2
        key0: {r: 1, g: 1, b: 1, a: 1}
        key1: {r: 1, g: 1, b: 1, a: 1}
        key2: {r: 0, g: 0, b: 0, a: 0}
        key3: {r: 0, g: 0, b: 0, a: 0}
        key4: {r: 0, g: 0, b: 0, a: 0}
        key5: {r: 0, g: 0, b: 0, a: 0}
        key6: {r: 0, g: 0, b: 0, a: 0}
        key7: {r: 0, g: 0, b: 0, a: 0}
        ctime0: 0
        ctime1: 65535
        ctime2: 0
        ctime3: 0
        ctime4: 0
        ctime5: 0
        ctime6: 0
        ctime7: 0
        atime0: 0
        atime1: 65535
        atime2: 0
        atime3: 0
        atime4: 0
        atime5: 0
        atime6: 0
        atime7: 0
        m_Mode: 0
        m_ColorSpace: -1
        m_NumColorKeys: 2
        m_NumAlphaKeys: 2
      minGradient:
        serializedVersion: 2
        key0: {r: 1, g: 1, b: 1, a: 1}
        key1: {r: 1, g: 1, b: 1, a: 1}
        key2: {r: 0, g: 0, b: 0, a: 0}
        key3: {r: 0, g: 0, b: 0, a: 0}
        key4: {r: 0, g: 0, b: 0, a: 0}
        key5: {r: 0, g: 0, b: 0, a: 0}
        key6: {r: 0, g: 0, b: 0, a: 0}
        key7: {r: 0, g: 0, b: 0, a: 0}
        ctime0: 0
        ctime1: 65535
        ctime2: 0
        ctime3: 0
        ctime4: 0
        ctime5: 0
        ctime6: 0
        ctime7: 0
        atime0: 0
        atime1: 65535
        atime2: 0
        atime3: 0
        atime4: 0
        atime5: 0
        atime6: 0
        atime7: 0
        m_Mode: 0
        m_ColorSpace: -1
        m_NumColorKeys: 2
        m_NumAlphaKeys: 2
  UVModule:
    serializedVersion: 2
    enabled: 0
    mode: 0
    timeMode: 0
    fps: 30
    frameOverTime:
      serializedVersion: 2
      minMaxState: 1
      scalar: 0.9999
      minScalar: 0.9999
      maxCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 0
          inSlope: 0
          outSlope: 1
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 1
          inSlope: 1
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
      minCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
    startFrame:
      serializedVersion: 2
      minMaxState: 0
      scalar: 0
      minScalar: 0
      maxCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
      minCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
    speedRange: {x: 0, y: 1}
    tilesX: 1
    tilesY: 1
    animationType: 0
    rowIndex: 0
    cycles: 1
    uvChannelMask: -1
    rowMode: 1
    sprites:
    - sprite: {fileID: 0}
    flipU: 0
    flipV: 0
  VelocityModule:
    enabled: 0
    x:
      serializedVersion: 2
      minMaxState: 0
      scalar: 0
      minScalar: 0
      maxCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
      minCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
    y:
      serializedVersion: 2
      minMaxState: 0
      scalar: 0
      minScalar: 0
      maxCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
      minCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
    z:
      serializedVersion: 2
      minMaxState: 0
      scalar: 0
      minScalar: 0
      maxCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
      minCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
    orbitalX:
      serializedVersion: 2
      minMaxState: 0
      scalar: 0
      minScalar: 0
      maxCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
      minCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
    orbitalY:
      serializedVersion: 2
      minMaxState: 0
      scalar: 0
      minScalar: 0
      maxCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
      minCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
    orbitalZ:
      serializedVersion: 2
      minMaxState: 0
      scalar: 0
      minScalar: 0
      maxCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
      minCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
    orbitalOffsetX:
      serializedVersion: 2
      minMaxState: 0
      scalar: 0
      minScalar: 0
      maxCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
      minCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
    orbitalOffsetY:
      serializedVersion: 2
      minMaxState: 0
      scalar: 0
      minScalar: 0
      maxCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
      minCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
    orbitalOffsetZ:
      serializedVersion: 2
      minMaxState: 0
      scalar: 0
      minScalar: 0
      maxCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
      minCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
    radial:
      serializedVersion: 2
      minMaxState: 0
      scalar: 0
      minScalar: 0
      maxCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
      minCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
    speedModifier:
      serializedVersion: 2
      minMaxState: 0
      scalar: 1
      minScalar: 1
      maxCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
      minCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
    inWorldSpace: 0
  InheritVelocityModule:
    enabled: 0
    m_Mode: 0
    m_Curve:
      serializedVersion: 2
      minMaxState: 0
      scalar: 0
      minScalar: 0
      maxCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
      minCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
  LifetimeByEmitterSpeedModule:
    enabled: 0
    m_Curve:
      serializedVersion: 2
      minMaxState: 1
      scalar: 1
      minScalar: 1
      maxCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 1
          inSlope: 0
          outSlope: -0.8
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 0.2
          inSlope: -0.8
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
      minCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
    m_Range: {x: 0, y: 1}
  ForceModule:
    enabled: 0
    x:
      serializedVersion: 2
      minMaxState: 0
      scalar: 0
      minScalar: 0
      maxCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
      minCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
    y:
      serializedVersion: 2
      minMaxState: 0
      scalar: 0
      minScalar: 0
      maxCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
      minCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
    z:
      serializedVersion: 2
      minMaxState: 0
      scalar: 0
      minScalar: 0
      maxCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
      minCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
    inWorldSpace: 0
    randomizePerFrame: 0
  ExternalForcesModule:
    serializedVersion: 2
    enabled: 0
    multiplierCurve:
      serializedVersion: 2
      minMaxState: 0
      scalar: 1
      minScalar: 1
      maxCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
      minCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
    influenceFilter: 0
    influenceMask:
      serializedVersion: 2
      m_Bits: 4294967295
    influenceList: []
  ClampVelocityModule:
    enabled: 0
    x:
      serializedVersion: 2
      minMaxState: 0
      scalar: 1
      minScalar: 1
      maxCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
      minCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
    y:
      serializedVersion: 2
      minMaxState: 0
      scalar: 1
      minScalar: 1
      maxCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
      minCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
    z:
      serializedVersion: 2
      minMaxState: 0
      scalar: 1
      minScalar: 1
      maxCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
      minCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
    magnitude:
      serializedVersion: 2
      minMaxState: 0
      scalar: 1
      minScalar: 1
      maxCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
      minCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
    separateAxis: 0
    inWorldSpace: 0
    multiplyDragByParticleSize: 1
    multiplyDragByParticleVelocity: 1
    dampen: 0
    drag:
      serializedVersion: 2
      minMaxState: 0
      scalar: 0
      minScalar: 0
      maxCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
      minCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
  NoiseModule:
    enabled: 0
    strength:
      serializedVersion: 2
      minMaxState: 0
      scalar: 1
      minScalar: 1
      maxCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
      minCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
    strengthY:
      serializedVersion: 2
      minMaxState: 0
      scalar: 1
      minScalar: 1
      maxCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
      minCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
    strengthZ:
      serializedVersion: 2
      minMaxState: 0
      scalar: 1
      minScalar: 1
      maxCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
      minCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
    separateAxes: 0
    frequency: 0.5
    damping: 1
    octaves: 1
    octaveMultiplier: 0.5
    octaveScale: 2
    quality: 1
    scrollSpeed:
      serializedVersion: 2
      minMaxState: 0
      scalar: 0
      minScalar: 0
      maxCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
      minCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
    remap:
      serializedVersion: 2
      minMaxState: 1
      scalar: 1
      minScalar: 1
      maxCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: -1
          inSlope: 0
          outSlope: 2
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 1
          inSlope: 2
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
      minCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
    remapY:
      serializedVersion: 2
      minMaxState: 1
      scalar: 1
      minScalar: 1
      maxCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: -1
          inSlope: 0
          outSlope: 2
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 1
          inSlope: 2
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
      minCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
    remapZ:
      serializedVersion: 2
      minMaxState: 1
      scalar: 1
      minScalar: 1
      maxCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: -1
          inSlope: 0
          outSlope: 2
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 1
          inSlope: 2
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
      minCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
    remapEnabled: 0
    positionAmount:
      serializedVersion: 2
      minMaxState: 0
      scalar: 1
      minScalar: 1
      maxCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
      minCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
    rotationAmount:
      serializedVersion: 2
      minMaxState: 0
      scalar: 0
      minScalar: 0
      maxCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
      minCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
    sizeAmount:
      serializedVersion: 2
      minMaxState: 0
      scalar: 0
      minScalar: 0
      maxCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
      minCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
  SizeBySpeedModule:
    enabled: 0
    curve:
      serializedVersion: 2
      minMaxState: 1
      scalar: 1
      minScalar: 1
      maxCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 0
          inSlope: 0
          outSlope: 1
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 1
          inSlope: 1
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
      minCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
    y:
      serializedVersion: 2
      minMaxState: 1
      scalar: 1
      minScalar: 1
      maxCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 0
          inSlope: 0
          outSlope: 1
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 1
          inSlope: 1
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
      minCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
    z:
      serializedVersion: 2
      minMaxState: 1
      scalar: 1
      minScalar: 1
      maxCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 0
          inSlope: 0
          outSlope: 1
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 1
          inSlope: 1
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
      minCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
    range: {x: 0, y: 1}
    separateAxes: 0
  RotationBySpeedModule:
    enabled: 0
    x:
      serializedVersion: 2
      minMaxState: 0
      scalar: 0
      minScalar: 0
      maxCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
      minCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
    y:
      serializedVersion: 2
      minMaxState: 0
      scalar: 0
      minScalar: 0
      maxCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
      minCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
    curve:
      serializedVersion: 2
      minMaxState: 0
      scalar: 0.7853982
      minScalar: 0.7853982
      maxCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
      minCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
    separateAxes: 0
    range: {x: 0, y: 1}
  ColorBySpeedModule:
    enabled: 0
    gradient:
      serializedVersion: 2
      minMaxState: 1
      minColor: {r: 1, g: 1, b: 1, a: 1}
      maxColor: {r: 1, g: 1, b: 1, a: 1}
      maxGradient:
        serializedVersion: 2
        key0: {r: 1, g: 1, b: 1, a: 1}
        key1: {r: 1, g: 1, b: 1, a: 1}
        key2: {r: 0, g: 0, b: 0, a: 0}
        key3: {r: 0, g: 0, b: 0, a: 0}
        key4: {r: 0, g: 0, b: 0, a: 0}
        key5: {r: 0, g: 0, b: 0, a: 0}
        key6: {r: 0, g: 0, b: 0, a: 0}
        key7: {r: 0, g: 0, b: 0, a: 0}
        ctime0: 0
        ctime1: 65535
        ctime2: 0
        ctime3: 0
        ctime4: 0
        ctime5: 0
        ctime6: 0
        ctime7: 0
        atime0: 0
        atime1: 65535
        atime2: 0
        atime3: 0
        atime4: 0
        atime5: 0
        atime6: 0
        atime7: 0
        m_Mode: 0
        m_ColorSpace: -1
        m_NumColorKeys: 2
        m_NumAlphaKeys: 2
      minGradient:
        serializedVersion: 2
        key0: {r: 1, g: 1, b: 1, a: 1}
        key1: {r: 1, g: 1, b: 1, a: 1}
        key2: {r: 0, g: 0, b: 0, a: 0}
        key3: {r: 0, g: 0, b: 0, a: 0}
        key4: {r: 0, g: 0, b: 0, a: 0}
        key5: {r: 0, g: 0, b: 0, a: 0}
        key6: {r: 0, g: 0, b: 0, a: 0}
        key7: {r: 0, g: 0, b: 0, a: 0}
        ctime0: 0
        ctime1: 65535
        ctime2: 0
        ctime3: 0
        ctime4: 0
        ctime5: 0
        ctime6: 0
        ctime7: 0
        atime0: 0
        atime1: 65535
        atime2: 0
        atime3: 0
        atime4: 0
        atime5: 0
        atime6: 0
        atime7: 0
        m_Mode: 0
        m_ColorSpace: -1
        m_NumColorKeys: 2
        m_NumAlphaKeys: 2
    range: {x: 0, y: 1}
  CollisionModule:
    enabled: 0
    serializedVersion: 4
    type: 0
    collisionMode: 0
    colliderForce: 0
    multiplyColliderForceByParticleSize: 0
    multiplyColliderForceByParticleSpeed: 0
    multiplyColliderForceByCollisionAngle: 1
    m_Planes: []
    m_Dampen:
      serializedVersion: 2
      minMaxState: 0
      scalar: 0
      minScalar: 0
      maxCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
      minCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
    m_Bounce:
      serializedVersion: 2
      minMaxState: 0
      scalar: 1
      minScalar: 1
      maxCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
      minCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
    m_EnergyLossOnCollision:
      serializedVersion: 2
      minMaxState: 0
      scalar: 0
      minScalar: 0
      maxCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
      minCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
    minKillSpeed: 0
    maxKillSpeed: 10000
    radiusScale: 1
    collidesWith:
      serializedVersion: 2
      m_Bits: 4294967295
    maxCollisionShapes: 256
    quality: 0
    voxelSize: 0.5
    collisionMessages: 0
    collidesWithDynamic: 1
    interiorCollisions: 0
  TriggerModule:
    enabled: 0
    serializedVersion: 2
    inside: 1
    outside: 0
    enter: 0
    exit: 0
    colliderQueryMode: 0
    radiusScale: 1
    primitives: []
  SubModule:
    serializedVersion: 2
    enabled: 0
    subEmitters:
    - serializedVersion: 3
      emitter: {fileID: 0}
      type: 0
      properties: 0
      emitProbability: 1
  LightsModule:
    enabled: 0
    ratio: 0
    light: {fileID: 0}
    randomDistribution: 1
    color: 1
    range: 1
    intensity: 1
    rangeCurve:
      serializedVersion: 2
      minMaxState: 0
      scalar: 1
      minScalar: 1
      maxCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
      minCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
    intensityCurve:
      serializedVersion: 2
      minMaxState: 0
      scalar: 1
      minScalar: 1
      maxCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
      minCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
    maxLights: 20
  TrailModule:
    enabled: 0
    mode: 0
    ratio: 1
    lifetime:
      serializedVersion: 2
      minMaxState: 0
      scalar: 1
      minScalar: 1
      maxCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
      minCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
    minVertexDistance: 0.2
    textureMode: 0
    textureScale: {x: 1, y: 1}
    ribbonCount: 1
    shadowBias: 0.5
    worldSpace: 0
    dieWithParticles: 1
    sizeAffectsWidth: 1
    sizeAffectsLifetime: 0
    inheritParticleColor: 1
    generateLightingData: 0
    splitSubEmitterRibbons: 0
    attachRibbonsToTransform: 0
    colorOverLifetime:
      serializedVersion: 2
      minMaxState: 0
      minColor: {r: 1, g: 1, b: 1, a: 1}
      maxColor: {r: 1, g: 1, b: 1, a: 1}
      maxGradient:
        serializedVersion: 2
        key0: {r: 1, g: 1, b: 1, a: 1}
        key1: {r: 1, g: 1, b: 1, a: 1}
        key2: {r: 0, g: 0, b: 0, a: 0}
        key3: {r: 0, g: 0, b: 0, a: 0}
        key4: {r: 0, g: 0, b: 0, a: 0}
        key5: {r: 0, g: 0, b: 0, a: 0}
        key6: {r: 0, g: 0, b: 0, a: 0}
        key7: {r: 0, g: 0, b: 0, a: 0}
        ctime0: 0
        ctime1: 65535
        ctime2: 0
        ctime3: 0
        ctime4: 0
        ctime5: 0
        ctime6: 0
        ctime7: 0
        atime0: 0
        atime1: 65535
        atime2: 0
        atime3: 0
        atime4: 0
        atime5: 0
        atime6: 0
        atime7: 0
        m_Mode: 0
        m_ColorSpace: -1
        m_NumColorKeys: 2
        m_NumAlphaKeys: 2
      minGradient:
        serializedVersion: 2
        key0: {r: 1, g: 1, b: 1, a: 1}
        key1: {r: 1, g: 1, b: 1, a: 1}
        key2: {r: 0, g: 0, b: 0, a: 0}
        key3: {r: 0, g: 0, b: 0, a: 0}
        key4: {r: 0, g: 0, b: 0, a: 0}
        key5: {r: 0, g: 0, b: 0, a: 0}
        key6: {r: 0, g: 0, b: 0, a: 0}
        key7: {r: 0, g: 0, b: 0, a: 0}
        ctime0: 0
        ctime1: 65535
        ctime2: 0
        ctime3: 0
        ctime4: 0
        ctime5: 0
        ctime6: 0
        ctime7: 0
        atime0: 0
        atime1: 65535
        atime2: 0
        atime3: 0
        atime4: 0
        atime5: 0
        atime6: 0
        atime7: 0
        m_Mode: 0
        m_ColorSpace: -1
        m_NumColorKeys: 2
        m_NumAlphaKeys: 2
    widthOverTrail:
      serializedVersion: 2
      minMaxState: 0
      scalar: 1
      minScalar: 1
      maxCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
      minCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
    colorOverTrail:
      serializedVersion: 2
      minMaxState: 0
      minColor: {r: 1, g: 1, b: 1, a: 1}
      maxColor: {r: 1, g: 1, b: 1, a: 1}
      maxGradient:
        serializedVersion: 2
        key0: {r: 1, g: 1, b: 1, a: 1}
        key1: {r: 1, g: 1, b: 1, a: 1}
        key2: {r: 0, g: 0, b: 0, a: 0}
        key3: {r: 0, g: 0, b: 0, a: 0}
        key4: {r: 0, g: 0, b: 0, a: 0}
        key5: {r: 0, g: 0, b: 0, a: 0}
        key6: {r: 0, g: 0, b: 0, a: 0}
        key7: {r: 0, g: 0, b: 0, a: 0}
        ctime0: 0
        ctime1: 65535
        ctime2: 0
        ctime3: 0
        ctime4: 0
        ctime5: 0
        ctime6: 0
        ctime7: 0
        atime0: 0
        atime1: 65535
        atime2: 0
        atime3: 0
        atime4: 0
        atime5: 0
        atime6: 0
        atime7: 0
        m_Mode: 0
        m_ColorSpace: -1
        m_NumColorKeys: 2
        m_NumAlphaKeys: 2
      minGradient:
        serializedVersion: 2
        key0: {r: 1, g: 1, b: 1, a: 1}
        key1: {r: 1, g: 1, b: 1, a: 1}
        key2: {r: 0, g: 0, b: 0, a: 0}
        key3: {r: 0, g: 0, b: 0, a: 0}
        key4: {r: 0, g: 0, b: 0, a: 0}
        key5: {r: 0, g: 0, b: 0, a: 0}
        key6: {r: 0, g: 0, b: 0, a: 0}
        key7: {r: 0, g: 0, b: 0, a: 0}
        ctime0: 0
        ctime1: 65535
        ctime2: 0
        ctime3: 0
        ctime4: 0
        ctime5: 0
        ctime6: 0
        ctime7: 0
        atime0: 0
        atime1: 65535
        atime2: 0
        atime3: 0
        atime4: 0
        atime5: 0
        atime6: 0
        atime7: 0
        m_Mode: 0
        m_ColorSpace: -1
        m_NumColorKeys: 2
        m_NumAlphaKeys: 2
  CustomDataModule:
    enabled: 0
    mode0: 0
    vectorComponentCount0: 4
    color0:
      serializedVersion: 2
      minMaxState: 0
      minColor: {r: 1, g: 1, b: 1, a: 1}
      maxColor: {r: 1, g: 1, b: 1, a: 1}
      maxGradient:
        serializedVersion: 2
        key0: {r: 1, g: 1, b: 1, a: 1}
        key1: {r: 1, g: 1, b: 1, a: 1}
        key2: {r: 0, g: 0, b: 0, a: 0}
        key3: {r: 0, g: 0, b: 0, a: 0}
        key4: {r: 0, g: 0, b: 0, a: 0}
        key5: {r: 0, g: 0, b: 0, a: 0}
        key6: {r: 0, g: 0, b: 0, a: 0}
        key7: {r: 0, g: 0, b: 0, a: 0}
        ctime0: 0
        ctime1: 65535
        ctime2: 0
        ctime3: 0
        ctime4: 0
        ctime5: 0
        ctime6: 0
        ctime7: 0
        atime0: 0
        atime1: 65535
        atime2: 0
        atime3: 0
        atime4: 0
        atime5: 0
        atime6: 0
        atime7: 0
        m_Mode: 0
        m_ColorSpace: -1
        m_NumColorKeys: 2
        m_NumAlphaKeys: 2
      minGradient:
        serializedVersion: 2
        key0: {r: 1, g: 1, b: 1, a: 1}
        key1: {r: 1, g: 1, b: 1, a: 1}
        key2: {r: 0, g: 0, b: 0, a: 0}
        key3: {r: 0, g: 0, b: 0, a: 0}
        key4: {r: 0, g: 0, b: 0, a: 0}
        key5: {r: 0, g: 0, b: 0, a: 0}
        key6: {r: 0, g: 0, b: 0, a: 0}
        key7: {r: 0, g: 0, b: 0, a: 0}
        ctime0: 0
        ctime1: 65535
        ctime2: 0
        ctime3: 0
        ctime4: 0
        ctime5: 0
        ctime6: 0
        ctime7: 0
        atime0: 0
        atime1: 65535
        atime2: 0
        atime3: 0
        atime4: 0
        atime5: 0
        atime6: 0
        atime7: 0
        m_Mode: 0
        m_ColorSpace: -1
        m_NumColorKeys: 2
        m_NumAlphaKeys: 2
    colorLabel0: Color
    vector0_0:
      serializedVersion: 2
      minMaxState: 0
      scalar: 0
      minScalar: 0
      maxCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
      minCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
    vectorLabel0_0: X
    vector0_1:
      serializedVersion: 2
      minMaxState: 0
      scalar: 0
      minScalar: 0
      maxCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
      minCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
    vectorLabel0_1: Y
    vector0_2:
      serializedVersion: 2
      minMaxState: 0
      scalar: 0
      minScalar: 0
      maxCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
      minCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
    vectorLabel0_2: Z
    vector0_3:
      serializedVersion: 2
      minMaxState: 0
      scalar: 0
      minScalar: 0
      maxCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
      minCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
    vectorLabel0_3: W
    mode1: 0
    vectorComponentCount1: 4
    color1:
      serializedVersion: 2
      minMaxState: 0
      minColor: {r: 1, g: 1, b: 1, a: 1}
      maxColor: {r: 1, g: 1, b: 1, a: 1}
      maxGradient:
        serializedVersion: 2
        key0: {r: 1, g: 1, b: 1, a: 1}
        key1: {r: 1, g: 1, b: 1, a: 1}
        key2: {r: 0, g: 0, b: 0, a: 0}
        key3: {r: 0, g: 0, b: 0, a: 0}
        key4: {r: 0, g: 0, b: 0, a: 0}
        key5: {r: 0, g: 0, b: 0, a: 0}
        key6: {r: 0, g: 0, b: 0, a: 0}
        key7: {r: 0, g: 0, b: 0, a: 0}
        ctime0: 0
        ctime1: 65535
        ctime2: 0
        ctime3: 0
        ctime4: 0
        ctime5: 0
        ctime6: 0
        ctime7: 0
        atime0: 0
        atime1: 65535
        atime2: 0
        atime3: 0
        atime4: 0
        atime5: 0
        atime6: 0
        atime7: 0
        m_Mode: 0
        m_ColorSpace: -1
        m_NumColorKeys: 2
        m_NumAlphaKeys: 2
      minGradient:
        serializedVersion: 2
        key0: {r: 1, g: 1, b: 1, a: 1}
        key1: {r: 1, g: 1, b: 1, a: 1}
        key2: {r: 0, g: 0, b: 0, a: 0}
        key3: {r: 0, g: 0, b: 0, a: 0}
        key4: {r: 0, g: 0, b: 0, a: 0}
        key5: {r: 0, g: 0, b: 0, a: 0}
        key6: {r: 0, g: 0, b: 0, a: 0}
        key7: {r: 0, g: 0, b: 0, a: 0}
        ctime0: 0
        ctime1: 65535
        ctime2: 0
        ctime3: 0
        ctime4: 0
        ctime5: 0
        ctime6: 0
        ctime7: 0
        atime0: 0
        atime1: 65535
        atime2: 0
        atime3: 0
        atime4: 0
        atime5: 0
        atime6: 0
        atime7: 0
        m_Mode: 0
        m_ColorSpace: -1
        m_NumColorKeys: 2
        m_NumAlphaKeys: 2
    colorLabel1: Color
    vector1_0:
      serializedVersion: 2
      minMaxState: 0
      scalar: 0
      minScalar: 0
      maxCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
      minCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
    vectorLabel1_0: X
    vector1_1:
      serializedVersion: 2
      minMaxState: 0
      scalar: 0
      minScalar: 0
      maxCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
      minCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
    vectorLabel1_1: Y
    vector1_2:
      serializedVersion: 2
      minMaxState: 0
      scalar: 0
      minScalar: 0
      maxCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
      minCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
    vectorLabel1_2: Z
    vector1_3:
      serializedVersion: 2
      minMaxState: 0
      scalar: 0
      minScalar: 0
      maxCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
      minCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
    vectorLabel1_3: W
--- !u!4 &842288767
Transform:
  m_ObjectHideFlags: 0
  m_CorrespondingSourceObject: {fileID: 0}
  m_PrefabInstance: {fileID: 0}
  m_PrefabAsset: {fileID: 0}
  m_GameObject: {fileID: 842288764}
  serializedVersion: 2
  m_LocalRotation: {x: -0.52407336, y: -0.13719898, z: 0.26993656, w: 0.7960263}
  m_LocalPosition: {x: -60.05, y: 89.54, z: 2.29}
  m_LocalScale: {x: 1, y: 1, z: 1}
  m_ConstrainProportionsScale: 0
  m_Children: []
  m_Father: {fileID: 0}
  m_LocalEulerAnglesHint: {x: -130.511, y: 129.483, z: -118}
--- !u!1 &854056114
GameObject:
  m_ObjectHideFlags: 0
  m_CorrespondingSourceObject: {fileID: 0}
  m_PrefabInstance: {fileID: 0}
  m_PrefabAsset: {fileID: 0}
  serializedVersion: 6
  m_Component:
  - component: {fileID: 854056116}
  - component: {fileID: 854056115}
  m_Layer: 0
  m_Name: Point Light (1)
  m_TagString: Untagged
  m_Icon: {fileID: 0}
  m_NavMeshLayer: 0
  m_StaticEditorFlags: 0
  m_IsActive: 1
--- !u!108 &854056115
Light:
  m_ObjectHideFlags: 0
  m_CorrespondingSourceObject: {fileID: 0}
  m_PrefabInstance: {fileID: 0}
  m_PrefabAsset: {fileID: 0}
  m_GameObject: {fileID: 854056114}
  m_Enabled: 1
  serializedVersion: 10
  m_Type: 2
  m_Shape: 0
  m_Color: {r: 1, g: 0.4411648, b: 0, a: 1}
  m_Intensity: 63
  m_Range: 17.1
  m_SpotAngle: 30
  m_InnerSpotAngle: 21.80208
  m_CookieSize: 10
  m_Shadows:
    m_Type: 0
    m_Resolution: -1
    m_CustomResolution: -1
    m_Strength: 1
    m_Bias: 0.05
    m_NormalBias: 0.4
    m_NearPlane: 0.2
    m_CullingMatrixOverride:
      e00: 1
      e01: 0
      e02: 0
      e03: 0
      e10: 0
      e11: 1
      e12: 0
      e13: 0
      e20: 0
      e21: 0
      e22: 1
      e23: 0
      e30: 0
      e31: 0
      e32: 0
      e33: 1
    m_UseCullingMatrixOverride: 0
  m_Cookie: {fileID: 0}
  m_DrawHalo: 0
  m_Flare: {fileID: 0}
  m_RenderMode: 0
  m_CullingMask:
    serializedVersion: 2
    m_Bits: 4294967295
  m_RenderingLayerMask: 1
  m_Lightmapping: 4
  m_LightShadowCasterMode: 0
  m_AreaSize: {x: 1, y: 1}
  m_BounceIntensity: 1
  m_ColorTemperature: 6570
  m_UseColorTemperature: 0
  m_BoundingSphereOverride: {x: 0, y: 0, z: 0, w: 0}
  m_UseBoundingSphereOverride: 0
  m_UseViewFrustumForShadowCasterCull: 1
  m_ShadowRadius: 0
  m_ShadowAngle: 0
--- !u!4 &854056116
Transform:
  m_ObjectHideFlags: 0
  m_CorrespondingSourceObject: {fileID: 0}
  m_PrefabInstance: {fileID: 0}
  m_PrefabAsset: {fileID: 0}
  m_GameObject: {fileID: 854056114}
  serializedVersion: 2
  m_LocalRotation: {x: 0, y: 0, z: 0, w: 1}
  m_LocalPosition: {x: -54.95, y: 88.81, z: -2.14}
  m_LocalScale: {x: 1, y: 1, z: 1}
  m_ConstrainProportionsScale: 0
  m_Children: []
  m_Father: {fileID: 0}
  m_LocalEulerAnglesHint: {x: 0, y: 0, z: 0}
--- !u!1 &963194225
GameObject:
  m_ObjectHideFlags: 0
  m_CorrespondingSourceObject: {fileID: 0}
  m_PrefabInstance: {fileID: 0}
  m_PrefabAsset: {fileID: 0}
  serializedVersion: 6
  m_Component:
  - component: {fileID: 963194228}
  - component: {fileID: 963194227}
  - component: {fileID: 963194226}
  m_Layer: 0
  m_Name: Main Camera
  m_TagString: MainCamera
  m_Icon: {fileID: 0}
  m_NavMeshLayer: 0
  m_StaticEditorFlags: 0
  m_IsActive: 1
--- !u!81 &963194226
AudioListener:
  m_ObjectHideFlags: 0
  m_CorrespondingSourceObject: {fileID: 0}
  m_PrefabInstance: {fileID: 0}
  m_PrefabAsset: {fileID: 0}
  m_GameObject: {fileID: 963194225}
  m_Enabled: 1
--- !u!20 &963194227
Camera:
  m_ObjectHideFlags: 0
  m_CorrespondingSourceObject: {fileID: 0}
  m_PrefabInstance: {fileID: 0}
  m_PrefabAsset: {fileID: 0}
  m_GameObject: {fileID: 963194225}
  m_Enabled: 1
  serializedVersion: 2
  m_ClearFlags: 1
  m_BackGroundColor: {r: 0.19215687, g: 0.3019608, b: 0.4745098, a: 0}
  m_projectionMatrixMode: 1
  m_GateFitMode: 2
  m_FOVAxisMode: 0
  m_Iso: 200
  m_ShutterSpeed: 0.005
  m_Aperture: 16
  m_FocusDistance: 10
  m_FocalLength: 50
  m_BladeCount: 5
  m_Curvature: {x: 2, y: 11}
  m_BarrelClipping: 0.25
  m_Anamorphism: 0
  m_SensorSize: {x: 36, y: 24}
  m_LensShift: {x: 0, y: 0}
  m_NormalizedViewPortRect:
    serializedVersion: 2
    x: 0
    y: 0
    width: 1
    height: 1
  near clip plane: 0.3
  far clip plane: 1000
  field of view: 60
  orthographic: 0
  orthographic size: 5
  m_Depth: -1
  m_CullingMask:
    serializedVersion: 2
    m_Bits: 4294967295
  m_RenderingPath: -1
  m_TargetTexture: {fileID: 0}
  m_TargetDisplay: 0
  m_TargetEye: 3
  m_HDR: 1
  m_AllowMSAA: 1
  m_AllowDynamicResolution: 0
  m_ForceIntoRT: 0
  m_OcclusionCulling: 1
  m_StereoConvergence: 10
  m_StereoSeparation: 0.022
--- !u!4 &963194228
Transform:
  m_ObjectHideFlags: 0
  m_CorrespondingSourceObject: {fileID: 0}
  m_PrefabInstance: {fileID: 0}
  m_PrefabAsset: {fileID: 0}
  m_GameObject: {fileID: 963194225}
  serializedVersion: 2
  m_LocalRotation: {x: 0.0843216, y: 0.7085536, z: -0.08592747, w: 0.6953116}
  m_LocalPosition: {x: -194.1, y: 138.8, z: 73.5}
  m_LocalScale: {x: 1, y: 1, z: 1}
  m_ConstrainProportionsScale: 0
  m_Children: []
  m_Father: {fileID: 0}
  m_LocalEulerAnglesHint: {x: 13.829, y: 91.081, z: 0}
--- !u!1 &1052382916
GameObject:
  m_ObjectHideFlags: 0
  m_CorrespondingSourceObject: {fileID: 0}
  m_PrefabInstance: {fileID: 0}
  m_PrefabAsset: {fileID: 0}
  serializedVersion: 6
  m_Component:
  - component: {fileID: 1052382919}
  - component: {fileID: 1052382918}
  - component: {fileID: 1052382917}
  m_Layer: 0
  m_Name: Particle System
  m_TagString: Untagged
  m_Icon: {fileID: 0}
  m_NavMeshLayer: 0
  m_StaticEditorFlags: 0
  m_IsActive: 1
--- !u!199 &1052382917
ParticleSystemRenderer:
  serializedVersion: 6
  m_ObjectHideFlags: 0
  m_CorrespondingSourceObject: {fileID: 0}
  m_PrefabInstance: {fileID: 0}
  m_PrefabAsset: {fileID: 0}
  m_GameObject: {fileID: 1052382916}
  m_Enabled: 1
  m_CastShadows: 0
  m_ReceiveShadows: 0
  m_DynamicOccludee: 1
  m_StaticShadowCaster: 0
  m_MotionVectors: 1
  m_LightProbeUsage: 0
  m_ReflectionProbeUsage: 0
  m_RayTracingMode: 0
  m_RayTraceProcedural: 0
  m_RenderingLayerMask: 1
  m_RendererPriority: 0
  m_Materials:
  - {fileID: 10308, guid: 0000000000000000f000000000000000, type: 0}
  m_StaticBatchInfo:
    firstSubMesh: 0
    subMeshCount: 0
  m_StaticBatchRoot: {fileID: 0}
  m_ProbeAnchor: {fileID: 0}
  m_LightProbeVolumeOverride: {fileID: 0}
  m_ScaleInLightmap: 1
  m_ReceiveGI: 1
  m_PreserveUVs: 0
  m_IgnoreNormalsForChartDetection: 0
  m_ImportantGI: 0
  m_StitchLightmapSeams: 1
  m_SelectedEditorRenderState: 3
  m_MinimumChartSize: 4
  m_AutoUVMaxDistance: 0.5
  m_AutoUVMaxAngle: 89
  m_LightmapParameters: {fileID: 0}
  m_SortingLayerID: 0
  m_SortingLayer: 0
  m_SortingOrder: 0
  m_RenderMode: 0
  m_MeshDistribution: 0
  m_SortMode: 0
  m_MinParticleSize: 0
  m_MaxParticleSize: 0.5
  m_CameraVelocityScale: 0
  m_VelocityScale: 0
  m_LengthScale: 2
  m_SortingFudge: 0
  m_NormalDirection: 1
  m_ShadowBias: 0
  m_RenderAlignment: 0
  m_Pivot: {x: 0, y: 0, z: 0}
  m_Flip: {x: 0, y: 0, z: 0}
  m_UseCustomVertexStreams: 0
  m_EnableGPUInstancing: 1
  m_ApplyActiveColorSpace: 1
  m_AllowRoll: 1
  m_FreeformStretching: 0
  m_RotateWithStretchDirection: 1
  m_VertexStreams: 00010304
  m_Mesh: {fileID: 0}
  m_Mesh1: {fileID: 0}
  m_Mesh2: {fileID: 0}
  m_Mesh3: {fileID: 0}
  m_MeshWeighting: 1
  m_MeshWeighting1: 1
  m_MeshWeighting2: 1
  m_MeshWeighting3: 1
  m_MaskInteraction: 0
--- !u!198 &1052382918
ParticleSystem:
  m_ObjectHideFlags: 0
  m_CorrespondingSourceObject: {fileID: 0}
  m_PrefabInstance: {fileID: 0}
  m_PrefabAsset: {fileID: 0}
  m_GameObject: {fileID: 1052382916}
  serializedVersion: 8
  lengthInSec: 5
  simulationSpeed: 1
  stopAction: 0
  cullingMode: 0
  ringBufferMode: 0
  ringBufferLoopRange: {x: 0, y: 1}
  emitterVelocityMode: 1
  looping: 1
  prewarm: 0
  playOnAwake: 1
  useUnscaledTime: 0
  autoRandomSeed: 1
  startDelay:
    serializedVersion: 2
    minMaxState: 0
    scalar: 0
    minScalar: 0
    maxCurve:
      serializedVersion: 2
      m_Curve:
      - serializedVersion: 3
        time: 0
        value: 0
        inSlope: 0
        outSlope: 0
        tangentMode: 0
        weightedMode: 0
        inWeight: 0.33333334
        outWeight: 0.33333334
      - serializedVersion: 3
        time: 1
        value: 0
        inSlope: 0
        outSlope: 0
        tangentMode: 0
        weightedMode: 0
        inWeight: 0.33333334
        outWeight: 0.33333334
      m_PreInfinity: 2
      m_PostInfinity: 2
      m_RotationOrder: 4
    minCurve:
      serializedVersion: 2
      m_Curve:
      - serializedVersion: 3
        time: 0
        value: 0
        inSlope: 0
        outSlope: 0
        tangentMode: 0
        weightedMode: 0
        inWeight: 0.33333334
        outWeight: 0.33333334
      - serializedVersion: 3
        time: 1
        value: 0
        inSlope: 0
        outSlope: 0
        tangentMode: 0
        weightedMode: 0
        inWeight: 0.33333334
        outWeight: 0.33333334
      m_PreInfinity: 2
      m_PostInfinity: 2
      m_RotationOrder: 4
  moveWithTransform: 0
  moveWithCustomTransform: {fileID: 0}
  scalingMode: 1
  randomSeed: 0
  InitialModule:
    serializedVersion: 3
    enabled: 1
    startLifetime:
      serializedVersion: 2
      minMaxState: 0
      scalar: 5
      minScalar: 5
      maxCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
      minCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
    startSpeed:
      serializedVersion: 2
      minMaxState: 0
      scalar: 5
      minScalar: 5
      maxCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
      minCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
    startColor:
      serializedVersion: 2
      minMaxState: 0
      minColor: {r: 1, g: 1, b: 1, a: 1}
      maxColor: {r: 1, g: 0.5061273, b: 0, a: 1}
      maxGradient:
        serializedVersion: 2
        key0: {r: 1, g: 1, b: 1, a: 1}
        key1: {r: 1, g: 1, b: 1, a: 1}
        key2: {r: 0, g: 0, b: 0, a: 0}
        key3: {r: 0, g: 0, b: 0, a: 0}
        key4: {r: 0, g: 0, b: 0, a: 0}
        key5: {r: 0, g: 0, b: 0, a: 0}
        key6: {r: 0, g: 0, b: 0, a: 0}
        key7: {r: 0, g: 0, b: 0, a: 0}
        ctime0: 0
        ctime1: 65535
        ctime2: 0
        ctime3: 0
        ctime4: 0
        ctime5: 0
        ctime6: 0
        ctime7: 0
        atime0: 0
        atime1: 65535
        atime2: 0
        atime3: 0
        atime4: 0
        atime5: 0
        atime6: 0
        atime7: 0
        m_Mode: 0
        m_ColorSpace: -1
        m_NumColorKeys: 2
        m_NumAlphaKeys: 2
      minGradient:
        serializedVersion: 2
        key0: {r: 1, g: 1, b: 1, a: 1}
        key1: {r: 1, g: 1, b: 1, a: 1}
        key2: {r: 0, g: 0, b: 0, a: 0}
        key3: {r: 0, g: 0, b: 0, a: 0}
        key4: {r: 0, g: 0, b: 0, a: 0}
        key5: {r: 0, g: 0, b: 0, a: 0}
        key6: {r: 0, g: 0, b: 0, a: 0}
        key7: {r: 0, g: 0, b: 0, a: 0}
        ctime0: 0
        ctime1: 65535
        ctime2: 0
        ctime3: 0
        ctime4: 0
        ctime5: 0
        ctime6: 0
        ctime7: 0
        atime0: 0
        atime1: 65535
        atime2: 0
        atime3: 0
        atime4: 0
        atime5: 0
        atime6: 0
        atime7: 0
        m_Mode: 0
        m_ColorSpace: -1
        m_NumColorKeys: 2
        m_NumAlphaKeys: 2
    startSize:
      serializedVersion: 2
      minMaxState: 0
      scalar: 1
      minScalar: 1
      maxCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
      minCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
    startSizeY:
      serializedVersion: 2
      minMaxState: 0
      scalar: 1
      minScalar: 1
      maxCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
      minCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
    startSizeZ:
      serializedVersion: 2
      minMaxState: 0
      scalar: 1
      minScalar: 1
      maxCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
      minCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
    startRotationX:
      serializedVersion: 2
      minMaxState: 0
      scalar: 0
      minScalar: 0
      maxCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
      minCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
    startRotationY:
      serializedVersion: 2
      minMaxState: 0
      scalar: 0
      minScalar: 0
      maxCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
      minCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
    startRotation:
      serializedVersion: 2
      minMaxState: 0
      scalar: 0
      minScalar: 0
      maxCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
      minCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
    randomizeRotationDirection: 0
    gravitySource: 0
    maxNumParticles: 1000
    customEmitterVelocity: {x: 0, y: 0, z: 0}
    size3D: 0
    rotation3D: 0
    gravityModifier:
      serializedVersion: 2
      minMaxState: 0
      scalar: 0
      minScalar: 0
      maxCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
      minCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
  ShapeModule:
    serializedVersion: 6
    enabled: 1
    type: 4
    angle: 25
    length: 5
    boxThickness: {x: 0, y: 0, z: 0}
    radiusThickness: 1
    donutRadius: 0.2
    m_Position: {x: 0, y: 0, z: 0}
    m_Rotation: {x: 0, y: 0, z: 0}
    m_Scale: {x: 1, y: 1, z: 1}
    placementMode: 0
    m_MeshMaterialIndex: 0
    m_MeshNormalOffset: 0
    m_MeshSpawn:
      mode: 0
      spread: 0
      speed:
        serializedVersion: 2
        minMaxState: 0
        scalar: 1
        minScalar: 1
        maxCurve:
          serializedVersion: 2
          m_Curve:
          - serializedVersion: 3
            time: 0
            value: 1
            inSlope: 0
            outSlope: 0
            tangentMode: 0
            weightedMode: 0
            inWeight: 0.33333334
            outWeight: 0.33333334
          - serializedVersion: 3
            time: 1
            value: 1
            inSlope: 0
            outSlope: 0
            tangentMode: 0
            weightedMode: 0
            inWeight: 0.33333334
            outWeight: 0.33333334
          m_PreInfinity: 2
          m_PostInfinity: 2
          m_RotationOrder: 4
        minCurve:
          serializedVersion: 2
          m_Curve:
          - serializedVersion: 3
            time: 0
            value: 1
            inSlope: 0
            outSlope: 0
            tangentMode: 0
            weightedMode: 0
            inWeight: 0.33333334
            outWeight: 0.33333334
          - serializedVersion: 3
            time: 1
            value: 1
            inSlope: 0
            outSlope: 0
            tangentMode: 0
            weightedMode: 0
            inWeight: 0.33333334
            outWeight: 0.33333334
          m_PreInfinity: 2
          m_PostInfinity: 2
          m_RotationOrder: 4
    m_Mesh: {fileID: 0}
    m_MeshRenderer: {fileID: 0}
    m_SkinnedMeshRenderer: {fileID: 0}
    m_Sprite: {fileID: 0}
    m_SpriteRenderer: {fileID: 0}
    m_UseMeshMaterialIndex: 0
    m_UseMeshColors: 1
    alignToDirection: 0
    m_Texture: {fileID: 0}
    m_TextureClipChannel: 3
    m_TextureClipThreshold: 0
    m_TextureUVChannel: 0
    m_TextureColorAffectsParticles: 1
    m_TextureAlphaAffectsParticles: 1
    m_TextureBilinearFiltering: 0
    randomDirectionAmount: 0
    sphericalDirectionAmount: 0
    randomPositionAmount: 0
    radius:
      value: 1
      mode: 0
      spread: 0
      speed:
        serializedVersion: 2
        minMaxState: 0
        scalar: 1
        minScalar: 1
        maxCurve:
          serializedVersion: 2
          m_Curve:
          - serializedVersion: 3
            time: 0
            value: 1
            inSlope: 0
            outSlope: 0
            tangentMode: 0
            weightedMode: 0
            inWeight: 0.33333334
            outWeight: 0.33333334
          - serializedVersion: 3
            time: 1
            value: 1
            inSlope: 0
            outSlope: 0
            tangentMode: 0
            weightedMode: 0
            inWeight: 0.33333334
            outWeight: 0.33333334
          m_PreInfinity: 2
          m_PostInfinity: 2
          m_RotationOrder: 4
        minCurve:
          serializedVersion: 2
          m_Curve:
          - serializedVersion: 3
            time: 0
            value: 1
            inSlope: 0
            outSlope: 0
            tangentMode: 0
            weightedMode: 0
            inWeight: 0.33333334
            outWeight: 0.33333334
          - serializedVersion: 3
            time: 1
            value: 1
            inSlope: 0
            outSlope: 0
            tangentMode: 0
            weightedMode: 0
            inWeight: 0.33333334
            outWeight: 0.33333334
          m_PreInfinity: 2
          m_PostInfinity: 2
          m_RotationOrder: 4
    arc:
      value: 360
      mode: 0
      spread: 0
      speed:
        serializedVersion: 2
        minMaxState: 0
        scalar: 1
        minScalar: 1
        maxCurve:
          serializedVersion: 2
          m_Curve:
          - serializedVersion: 3
            time: 0
            value: 1
            inSlope: 0
            outSlope: 0
            tangentMode: 0
            weightedMode: 0
            inWeight: 0.33333334
            outWeight: 0.33333334
          - serializedVersion: 3
            time: 1
            value: 1
            inSlope: 0
            outSlope: 0
            tangentMode: 0
            weightedMode: 0
            inWeight: 0.33333334
            outWeight: 0.33333334
          m_PreInfinity: 2
          m_PostInfinity: 2
          m_RotationOrder: 4
        minCurve:
          serializedVersion: 2
          m_Curve:
          - serializedVersion: 3
            time: 0
            value: 1
            inSlope: 0
            outSlope: 0
            tangentMode: 0
            weightedMode: 0
            inWeight: 0.33333334
            outWeight: 0.33333334
          - serializedVersion: 3
            time: 1
            value: 1
            inSlope: 0
            outSlope: 0
            tangentMode: 0
            weightedMode: 0
            inWeight: 0.33333334
            outWeight: 0.33333334
          m_PreInfinity: 2
          m_PostInfinity: 2
          m_RotationOrder: 4
  EmissionModule:
    enabled: 1
    serializedVersion: 4
    rateOverTime:
      serializedVersion: 2
      minMaxState: 0
      scalar: 10
      minScalar: 10
      maxCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
      minCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
    rateOverDistance:
      serializedVersion: 2
      minMaxState: 0
      scalar: 0
      minScalar: 0
      maxCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
      minCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
    m_BurstCount: 0
    m_Bursts: []
  SizeModule:
    enabled: 0
    curve:
      serializedVersion: 2
      minMaxState: 1
      scalar: 1
      minScalar: 1
      maxCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 0
          inSlope: 0
          outSlope: 1
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 1
          inSlope: 1
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
      minCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
    y:
      serializedVersion: 2
      minMaxState: 1
      scalar: 1
      minScalar: 1
      maxCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 0
          inSlope: 0
          outSlope: 1
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 1
          inSlope: 1
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
      minCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
    z:
      serializedVersion: 2
      minMaxState: 1
      scalar: 1
      minScalar: 1
      maxCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 0
          inSlope: 0
          outSlope: 1
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 1
          inSlope: 1
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
      minCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
    separateAxes: 0
  RotationModule:
    enabled: 0
    x:
      serializedVersion: 2
      minMaxState: 0
      scalar: 0
      minScalar: 0
      maxCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
      minCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
    y:
      serializedVersion: 2
      minMaxState: 0
      scalar: 0
      minScalar: 0
      maxCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
      minCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
    curve:
      serializedVersion: 2
      minMaxState: 0
      scalar: 0.7853982
      minScalar: 0.7853982
      maxCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
      minCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
    separateAxes: 0
  ColorModule:
    enabled: 0
    gradient:
      serializedVersion: 2
      minMaxState: 1
      minColor: {r: 1, g: 1, b: 1, a: 1}
      maxColor: {r: 1, g: 1, b: 1, a: 1}
      maxGradient:
        serializedVersion: 2
        key0: {r: 1, g: 1, b: 1, a: 1}
        key1: {r: 1, g: 1, b: 1, a: 1}
        key2: {r: 0, g: 0, b: 0, a: 0}
        key3: {r: 0, g: 0, b: 0, a: 0}
        key4: {r: 0, g: 0, b: 0, a: 0}
        key5: {r: 0, g: 0, b: 0, a: 0}
        key6: {r: 0, g: 0, b: 0, a: 0}
        key7: {r: 0, g: 0, b: 0, a: 0}
        ctime0: 0
        ctime1: 65535
        ctime2: 0
        ctime3: 0
        ctime4: 0
        ctime5: 0
        ctime6: 0
        ctime7: 0
        atime0: 0
        atime1: 65535
        atime2: 0
        atime3: 0
        atime4: 0
        atime5: 0
        atime6: 0
        atime7: 0
        m_Mode: 0
        m_ColorSpace: -1
        m_NumColorKeys: 2
        m_NumAlphaKeys: 2
      minGradient:
        serializedVersion: 2
        key0: {r: 1, g: 1, b: 1, a: 1}
        key1: {r: 1, g: 1, b: 1, a: 1}
        key2: {r: 0, g: 0, b: 0, a: 0}
        key3: {r: 0, g: 0, b: 0, a: 0}
        key4: {r: 0, g: 0, b: 0, a: 0}
        key5: {r: 0, g: 0, b: 0, a: 0}
        key6: {r: 0, g: 0, b: 0, a: 0}
        key7: {r: 0, g: 0, b: 0, a: 0}
        ctime0: 0
        ctime1: 65535
        ctime2: 0
        ctime3: 0
        ctime4: 0
        ctime5: 0
        ctime6: 0
        ctime7: 0
        atime0: 0
        atime1: 65535
        atime2: 0
        atime3: 0
        atime4: 0
        atime5: 0
        atime6: 0
        atime7: 0
        m_Mode: 0
        m_ColorSpace: -1
        m_NumColorKeys: 2
        m_NumAlphaKeys: 2
  UVModule:
    serializedVersion: 2
    enabled: 0
    mode: 0
    timeMode: 0
    fps: 30
    frameOverTime:
      serializedVersion: 2
      minMaxState: 1
      scalar: 0.9999
      minScalar: 0.9999
      maxCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 0
          inSlope: 0
          outSlope: 1
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 1
          inSlope: 1
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
      minCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
    startFrame:
      serializedVersion: 2
      minMaxState: 0
      scalar: 0
      minScalar: 0
      maxCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
      minCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
    speedRange: {x: 0, y: 1}
    tilesX: 1
    tilesY: 1
    animationType: 0
    rowIndex: 0
    cycles: 1
    uvChannelMask: -1
    rowMode: 1
    sprites:
    - sprite: {fileID: 0}
    flipU: 0
    flipV: 0
  VelocityModule:
    enabled: 0
    x:
      serializedVersion: 2
      minMaxState: 0
      scalar: 0
      minScalar: 0
      maxCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
      minCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
    y:
      serializedVersion: 2
      minMaxState: 0
      scalar: 0
      minScalar: 0
      maxCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
      minCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
    z:
      serializedVersion: 2
      minMaxState: 0
      scalar: 0
      minScalar: 0
      maxCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
      minCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
    orbitalX:
      serializedVersion: 2
      minMaxState: 0
      scalar: 0
      minScalar: 0
      maxCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
      minCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
    orbitalY:
      serializedVersion: 2
      minMaxState: 0
      scalar: 0
      minScalar: 0
      maxCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
      minCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
    orbitalZ:
      serializedVersion: 2
      minMaxState: 0
      scalar: 0
      minScalar: 0
      maxCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
      minCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
    orbitalOffsetX:
      serializedVersion: 2
      minMaxState: 0
      scalar: 0
      minScalar: 0
      maxCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
      minCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
    orbitalOffsetY:
      serializedVersion: 2
      minMaxState: 0
      scalar: 0
      minScalar: 0
      maxCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
      minCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
    orbitalOffsetZ:
      serializedVersion: 2
      minMaxState: 0
      scalar: 0
      minScalar: 0
      maxCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
      minCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
    radial:
      serializedVersion: 2
      minMaxState: 0
      scalar: 0
      minScalar: 0
      maxCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
      minCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
    speedModifier:
      serializedVersion: 2
      minMaxState: 0
      scalar: 1
      minScalar: 1
      maxCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
      minCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
    inWorldSpace: 0
  InheritVelocityModule:
    enabled: 0
    m_Mode: 0
    m_Curve:
      serializedVersion: 2
      minMaxState: 0
      scalar: 0
      minScalar: 0
      maxCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
      minCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
  LifetimeByEmitterSpeedModule:
    enabled: 0
    m_Curve:
      serializedVersion: 2
      minMaxState: 1
      scalar: 1
      minScalar: 1
      maxCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 1
          inSlope: 0
          outSlope: -0.8
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 0.2
          inSlope: -0.8
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
      minCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
    m_Range: {x: 0, y: 1}
  ForceModule:
    enabled: 0
    x:
      serializedVersion: 2
      minMaxState: 0
      scalar: 0
      minScalar: 0
      maxCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
      minCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
    y:
      serializedVersion: 2
      minMaxState: 0
      scalar: 0
      minScalar: 0
      maxCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
      minCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
    z:
      serializedVersion: 2
      minMaxState: 0
      scalar: 0
      minScalar: 0
      maxCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
      minCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
    inWorldSpace: 0
    randomizePerFrame: 0
  ExternalForcesModule:
    serializedVersion: 2
    enabled: 0
    multiplierCurve:
      serializedVersion: 2
      minMaxState: 0
      scalar: 1
      minScalar: 1
      maxCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
      minCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
    influenceFilter: 0
    influenceMask:
      serializedVersion: 2
      m_Bits: 4294967295
    influenceList: []
  ClampVelocityModule:
    enabled: 0
    x:
      serializedVersion: 2
      minMaxState: 0
      scalar: 1
      minScalar: 1
      maxCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
      minCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
    y:
      serializedVersion: 2
      minMaxState: 0
      scalar: 1
      minScalar: 1
      maxCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
      minCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
    z:
      serializedVersion: 2
      minMaxState: 0
      scalar: 1
      minScalar: 1
      maxCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
      minCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
    magnitude:
      serializedVersion: 2
      minMaxState: 0
      scalar: 1
      minScalar: 1
      maxCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
      minCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
    separateAxis: 0
    inWorldSpace: 0
    multiplyDragByParticleSize: 1
    multiplyDragByParticleVelocity: 1
    dampen: 0
    drag:
      serializedVersion: 2
      minMaxState: 0
      scalar: 0
      minScalar: 0
      maxCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
      minCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
  NoiseModule:
    enabled: 0
    strength:
      serializedVersion: 2
      minMaxState: 0
      scalar: 1
      minScalar: 1
      maxCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
      minCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
    strengthY:
      serializedVersion: 2
      minMaxState: 0
      scalar: 1
      minScalar: 1
      maxCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
      minCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
    strengthZ:
      serializedVersion: 2
      minMaxState: 0
      scalar: 1
      minScalar: 1
      maxCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
      minCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
    separateAxes: 0
    frequency: 0.5
    damping: 1
    octaves: 1
    octaveMultiplier: 0.5
    octaveScale: 2
    quality: 1
    scrollSpeed:
      serializedVersion: 2
      minMaxState: 0
      scalar: 0
      minScalar: 0
      maxCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
      minCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
    remap:
      serializedVersion: 2
      minMaxState: 1
      scalar: 1
      minScalar: 1
      maxCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: -1
          inSlope: 0
          outSlope: 2
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 1
          inSlope: 2
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
      minCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
    remapY:
      serializedVersion: 2
      minMaxState: 1
      scalar: 1
      minScalar: 1
      maxCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: -1
          inSlope: 0
          outSlope: 2
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 1
          inSlope: 2
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
      minCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
    remapZ:
      serializedVersion: 2
      minMaxState: 1
      scalar: 1
      minScalar: 1
      maxCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: -1
          inSlope: 0
          outSlope: 2
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 1
          inSlope: 2
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
      minCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
    remapEnabled: 0
    positionAmount:
      serializedVersion: 2
      minMaxState: 0
      scalar: 1
      minScalar: 1
      maxCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
      minCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
    rotationAmount:
      serializedVersion: 2
      minMaxState: 0
      scalar: 0
      minScalar: 0
      maxCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
      minCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
    sizeAmount:
      serializedVersion: 2
      minMaxState: 0
      scalar: 0
      minScalar: 0
      maxCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
      minCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
  SizeBySpeedModule:
    enabled: 0
    curve:
      serializedVersion: 2
      minMaxState: 1
      scalar: 1
      minScalar: 1
      maxCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 0
          inSlope: 0
          outSlope: 1
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 1
          inSlope: 1
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
      minCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
    y:
      serializedVersion: 2
      minMaxState: 1
      scalar: 1
      minScalar: 1
      maxCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 0
          inSlope: 0
          outSlope: 1
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 1
          inSlope: 1
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
      minCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
    z:
      serializedVersion: 2
      minMaxState: 1
      scalar: 1
      minScalar: 1
      maxCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 0
          inSlope: 0
          outSlope: 1
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 1
          inSlope: 1
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
      minCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
    range: {x: 0, y: 1}
    separateAxes: 0
  RotationBySpeedModule:
    enabled: 0
    x:
      serializedVersion: 2
      minMaxState: 0
      scalar: 0
      minScalar: 0
      maxCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
      minCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
    y:
      serializedVersion: 2
      minMaxState: 0
      scalar: 0
      minScalar: 0
      maxCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
      minCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
    curve:
      serializedVersion: 2
      minMaxState: 0
      scalar: 0.7853982
      minScalar: 0.7853982
      maxCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
      minCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
    separateAxes: 0
    range: {x: 0, y: 1}
  ColorBySpeedModule:
    enabled: 0
    gradient:
      serializedVersion: 2
      minMaxState: 1
      minColor: {r: 1, g: 1, b: 1, a: 1}
      maxColor: {r: 1, g: 1, b: 1, a: 1}
      maxGradient:
        serializedVersion: 2
        key0: {r: 1, g: 1, b: 1, a: 1}
        key1: {r: 1, g: 1, b: 1, a: 1}
        key2: {r: 0, g: 0, b: 0, a: 0}
        key3: {r: 0, g: 0, b: 0, a: 0}
        key4: {r: 0, g: 0, b: 0, a: 0}
        key5: {r: 0, g: 0, b: 0, a: 0}
        key6: {r: 0, g: 0, b: 0, a: 0}
        key7: {r: 0, g: 0, b: 0, a: 0}
        ctime0: 0
        ctime1: 65535
        ctime2: 0
        ctime3: 0
        ctime4: 0
        ctime5: 0
        ctime6: 0
        ctime7: 0
        atime0: 0
        atime1: 65535
        atime2: 0
        atime3: 0
        atime4: 0
        atime5: 0
        atime6: 0
        atime7: 0
        m_Mode: 0
        m_ColorSpace: -1
        m_NumColorKeys: 2
        m_NumAlphaKeys: 2
      minGradient:
        serializedVersion: 2
        key0: {r: 1, g: 1, b: 1, a: 1}
        key1: {r: 1, g: 1, b: 1, a: 1}
        key2: {r: 0, g: 0, b: 0, a: 0}
        key3: {r: 0, g: 0, b: 0, a: 0}
        key4: {r: 0, g: 0, b: 0, a: 0}
        key5: {r: 0, g: 0, b: 0, a: 0}
        key6: {r: 0, g: 0, b: 0, a: 0}
        key7: {r: 0, g: 0, b: 0, a: 0}
        ctime0: 0
        ctime1: 65535
        ctime2: 0
        ctime3: 0
        ctime4: 0
        ctime5: 0
        ctime6: 0
        ctime7: 0
        atime0: 0
        atime1: 65535
        atime2: 0
        atime3: 0
        atime4: 0
        atime5: 0
        atime6: 0
        atime7: 0
        m_Mode: 0
        m_ColorSpace: -1
        m_NumColorKeys: 2
        m_NumAlphaKeys: 2
    range: {x: 0, y: 1}
  CollisionModule:
    enabled: 0
    serializedVersion: 4
    type: 0
    collisionMode: 0
    colliderForce: 0
    multiplyColliderForceByParticleSize: 0
    multiplyColliderForceByParticleSpeed: 0
    multiplyColliderForceByCollisionAngle: 1
    m_Planes: []
    m_Dampen:
      serializedVersion: 2
      minMaxState: 0
      scalar: 0
      minScalar: 0
      maxCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
      minCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
    m_Bounce:
      serializedVersion: 2
      minMaxState: 0
      scalar: 1
      minScalar: 1
      maxCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
      minCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
    m_EnergyLossOnCollision:
      serializedVersion: 2
      minMaxState: 0
      scalar: 0
      minScalar: 0
      maxCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
      minCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
    minKillSpeed: 0
    maxKillSpeed: 10000
    radiusScale: 1
    collidesWith:
      serializedVersion: 2
      m_Bits: 4294967295
    maxCollisionShapes: 256
    quality: 0
    voxelSize: 0.5
    collisionMessages: 0
    collidesWithDynamic: 1
    interiorCollisions: 0
  TriggerModule:
    enabled: 0
    serializedVersion: 2
    inside: 1
    outside: 0
    enter: 0
    exit: 0
    colliderQueryMode: 0
    radiusScale: 1
    primitives: []
  SubModule:
    serializedVersion: 2
    enabled: 0
    subEmitters:
    - serializedVersion: 3
      emitter: {fileID: 0}
      type: 0
      properties: 0
      emitProbability: 1
  LightsModule:
    enabled: 0
    ratio: 0
    light: {fileID: 0}
    randomDistribution: 1
    color: 1
    range: 1
    intensity: 1
    rangeCurve:
      serializedVersion: 2
      minMaxState: 0
      scalar: 1
      minScalar: 1
      maxCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
      minCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
    intensityCurve:
      serializedVersion: 2
      minMaxState: 0
      scalar: 1
      minScalar: 1
      maxCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
      minCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
    maxLights: 20
  TrailModule:
    enabled: 0
    mode: 0
    ratio: 1
    lifetime:
      serializedVersion: 2
      minMaxState: 0
      scalar: 1
      minScalar: 1
      maxCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
      minCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
    minVertexDistance: 0.2
    textureMode: 0
    textureScale: {x: 1, y: 1}
    ribbonCount: 1
    shadowBias: 0.5
    worldSpace: 0
    dieWithParticles: 1
    sizeAffectsWidth: 1
    sizeAffectsLifetime: 0
    inheritParticleColor: 1
    generateLightingData: 0
    splitSubEmitterRibbons: 0
    attachRibbonsToTransform: 0
    colorOverLifetime:
      serializedVersion: 2
      minMaxState: 0
      minColor: {r: 1, g: 1, b: 1, a: 1}
      maxColor: {r: 1, g: 1, b: 1, a: 1}
      maxGradient:
        serializedVersion: 2
        key0: {r: 1, g: 1, b: 1, a: 1}
        key1: {r: 1, g: 1, b: 1, a: 1}
        key2: {r: 0, g: 0, b: 0, a: 0}
        key3: {r: 0, g: 0, b: 0, a: 0}
        key4: {r: 0, g: 0, b: 0, a: 0}
        key5: {r: 0, g: 0, b: 0, a: 0}
        key6: {r: 0, g: 0, b: 0, a: 0}
        key7: {r: 0, g: 0, b: 0, a: 0}
        ctime0: 0
        ctime1: 65535
        ctime2: 0
        ctime3: 0
        ctime4: 0
        ctime5: 0
        ctime6: 0
        ctime7: 0
        atime0: 0
        atime1: 65535
        atime2: 0
        atime3: 0
        atime4: 0
        atime5: 0
        atime6: 0
        atime7: 0
        m_Mode: 0
        m_ColorSpace: -1
        m_NumColorKeys: 2
        m_NumAlphaKeys: 2
      minGradient:
        serializedVersion: 2
        key0: {r: 1, g: 1, b: 1, a: 1}
        key1: {r: 1, g: 1, b: 1, a: 1}
        key2: {r: 0, g: 0, b: 0, a: 0}
        key3: {r: 0, g: 0, b: 0, a: 0}
        key4: {r: 0, g: 0, b: 0, a: 0}
        key5: {r: 0, g: 0, b: 0, a: 0}
        key6: {r: 0, g: 0, b: 0, a: 0}
        key7: {r: 0, g: 0, b: 0, a: 0}
        ctime0: 0
        ctime1: 65535
        ctime2: 0
        ctime3: 0
        ctime4: 0
        ctime5: 0
        ctime6: 0
        ctime7: 0
        atime0: 0
        atime1: 65535
        atime2: 0
        atime3: 0
        atime4: 0
        atime5: 0
        atime6: 0
        atime7: 0
        m_Mode: 0
        m_ColorSpace: -1
        m_NumColorKeys: 2
        m_NumAlphaKeys: 2
    widthOverTrail:
      serializedVersion: 2
      minMaxState: 0
      scalar: 1
      minScalar: 1
      maxCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
      minCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 1
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
    colorOverTrail:
      serializedVersion: 2
      minMaxState: 0
      minColor: {r: 1, g: 1, b: 1, a: 1}
      maxColor: {r: 1, g: 1, b: 1, a: 1}
      maxGradient:
        serializedVersion: 2
        key0: {r: 1, g: 1, b: 1, a: 1}
        key1: {r: 1, g: 1, b: 1, a: 1}
        key2: {r: 0, g: 0, b: 0, a: 0}
        key3: {r: 0, g: 0, b: 0, a: 0}
        key4: {r: 0, g: 0, b: 0, a: 0}
        key5: {r: 0, g: 0, b: 0, a: 0}
        key6: {r: 0, g: 0, b: 0, a: 0}
        key7: {r: 0, g: 0, b: 0, a: 0}
        ctime0: 0
        ctime1: 65535
        ctime2: 0
        ctime3: 0
        ctime4: 0
        ctime5: 0
        ctime6: 0
        ctime7: 0
        atime0: 0
        atime1: 65535
        atime2: 0
        atime3: 0
        atime4: 0
        atime5: 0
        atime6: 0
        atime7: 0
        m_Mode: 0
        m_ColorSpace: -1
        m_NumColorKeys: 2
        m_NumAlphaKeys: 2
      minGradient:
        serializedVersion: 2
        key0: {r: 1, g: 1, b: 1, a: 1}
        key1: {r: 1, g: 1, b: 1, a: 1}
        key2: {r: 0, g: 0, b: 0, a: 0}
        key3: {r: 0, g: 0, b: 0, a: 0}
        key4: {r: 0, g: 0, b: 0, a: 0}
        key5: {r: 0, g: 0, b: 0, a: 0}
        key6: {r: 0, g: 0, b: 0, a: 0}
        key7: {r: 0, g: 0, b: 0, a: 0}
        ctime0: 0
        ctime1: 65535
        ctime2: 0
        ctime3: 0
        ctime4: 0
        ctime5: 0
        ctime6: 0
        ctime7: 0
        atime0: 0
        atime1: 65535
        atime2: 0
        atime3: 0
        atime4: 0
        atime5: 0
        atime6: 0
        atime7: 0
        m_Mode: 0
        m_ColorSpace: -1
        m_NumColorKeys: 2
        m_NumAlphaKeys: 2
  CustomDataModule:
    enabled: 0
    mode0: 0
    vectorComponentCount0: 4
    color0:
      serializedVersion: 2
      minMaxState: 0
      minColor: {r: 1, g: 1, b: 1, a: 1}
      maxColor: {r: 1, g: 1, b: 1, a: 1}
      maxGradient:
        serializedVersion: 2
        key0: {r: 1, g: 1, b: 1, a: 1}
        key1: {r: 1, g: 1, b: 1, a: 1}
        key2: {r: 0, g: 0, b: 0, a: 0}
        key3: {r: 0, g: 0, b: 0, a: 0}
        key4: {r: 0, g: 0, b: 0, a: 0}
        key5: {r: 0, g: 0, b: 0, a: 0}
        key6: {r: 0, g: 0, b: 0, a: 0}
        key7: {r: 0, g: 0, b: 0, a: 0}
        ctime0: 0
        ctime1: 65535
        ctime2: 0
        ctime3: 0
        ctime4: 0
        ctime5: 0
        ctime6: 0
        ctime7: 0
        atime0: 0
        atime1: 65535
        atime2: 0
        atime3: 0
        atime4: 0
        atime5: 0
        atime6: 0
        atime7: 0
        m_Mode: 0
        m_ColorSpace: -1
        m_NumColorKeys: 2
        m_NumAlphaKeys: 2
      minGradient:
        serializedVersion: 2
        key0: {r: 1, g: 1, b: 1, a: 1}
        key1: {r: 1, g: 1, b: 1, a: 1}
        key2: {r: 0, g: 0, b: 0, a: 0}
        key3: {r: 0, g: 0, b: 0, a: 0}
        key4: {r: 0, g: 0, b: 0, a: 0}
        key5: {r: 0, g: 0, b: 0, a: 0}
        key6: {r: 0, g: 0, b: 0, a: 0}
        key7: {r: 0, g: 0, b: 0, a: 0}
        ctime0: 0
        ctime1: 65535
        ctime2: 0
        ctime3: 0
        ctime4: 0
        ctime5: 0
        ctime6: 0
        ctime7: 0
        atime0: 0
        atime1: 65535
        atime2: 0
        atime3: 0
        atime4: 0
        atime5: 0
        atime6: 0
        atime7: 0
        m_Mode: 0
        m_ColorSpace: -1
        m_NumColorKeys: 2
        m_NumAlphaKeys: 2
    colorLabel0: Color
    vector0_0:
      serializedVersion: 2
      minMaxState: 0
      scalar: 0
      minScalar: 0
      maxCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
      minCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
    vectorLabel0_0: X
    vector0_1:
      serializedVersion: 2
      minMaxState: 0
      scalar: 0
      minScalar: 0
      maxCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
      minCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
    vectorLabel0_1: Y
    vector0_2:
      serializedVersion: 2
      minMaxState: 0
      scalar: 0
      minScalar: 0
      maxCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
      minCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
    vectorLabel0_2: Z
    vector0_3:
      serializedVersion: 2
      minMaxState: 0
      scalar: 0
      minScalar: 0
      maxCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
      minCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
    vectorLabel0_3: W
    mode1: 0
    vectorComponentCount1: 4
    color1:
      serializedVersion: 2
      minMaxState: 0
      minColor: {r: 1, g: 1, b: 1, a: 1}
      maxColor: {r: 1, g: 1, b: 1, a: 1}
      maxGradient:
        serializedVersion: 2
        key0: {r: 1, g: 1, b: 1, a: 1}
        key1: {r: 1, g: 1, b: 1, a: 1}
        key2: {r: 0, g: 0, b: 0, a: 0}
        key3: {r: 0, g: 0, b: 0, a: 0}
        key4: {r: 0, g: 0, b: 0, a: 0}
        key5: {r: 0, g: 0, b: 0, a: 0}
        key6: {r: 0, g: 0, b: 0, a: 0}
        key7: {r: 0, g: 0, b: 0, a: 0}
        ctime0: 0
        ctime1: 65535
        ctime2: 0
        ctime3: 0
        ctime4: 0
        ctime5: 0
        ctime6: 0
        ctime7: 0
        atime0: 0
        atime1: 65535
        atime2: 0
        atime3: 0
        atime4: 0
        atime5: 0
        atime6: 0
        atime7: 0
        m_Mode: 0
        m_ColorSpace: -1
        m_NumColorKeys: 2
        m_NumAlphaKeys: 2
      minGradient:
        serializedVersion: 2
        key0: {r: 1, g: 1, b: 1, a: 1}
        key1: {r: 1, g: 1, b: 1, a: 1}
        key2: {r: 0, g: 0, b: 0, a: 0}
        key3: {r: 0, g: 0, b: 0, a: 0}
        key4: {r: 0, g: 0, b: 0, a: 0}
        key5: {r: 0, g: 0, b: 0, a: 0}
        key6: {r: 0, g: 0, b: 0, a: 0}
        key7: {r: 0, g: 0, b: 0, a: 0}
        ctime0: 0
        ctime1: 65535
        ctime2: 0
        ctime3: 0
        ctime4: 0
        ctime5: 0
        ctime6: 0
        ctime7: 0
        atime0: 0
        atime1: 65535
        atime2: 0
        atime3: 0
        atime4: 0
        atime5: 0
        atime6: 0
        atime7: 0
        m_Mode: 0
        m_ColorSpace: -1
        m_NumColorKeys: 2
        m_NumAlphaKeys: 2
    colorLabel1: Color
    vector1_0:
      serializedVersion: 2
      minMaxState: 0
      scalar: 0
      minScalar: 0
      maxCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
      minCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
    vectorLabel1_0: X
    vector1_1:
      serializedVersion: 2
      minMaxState: 0
      scalar: 0
      minScalar: 0
      maxCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
      minCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
    vectorLabel1_1: Y
    vector1_2:
      serializedVersion: 2
      minMaxState: 0
      scalar: 0
      minScalar: 0
      maxCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
      minCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
    vectorLabel1_2: Z
    vector1_3:
      serializedVersion: 2
      minMaxState: 0
      scalar: 0
      minScalar: 0
      maxCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
      minCurve:
        serializedVersion: 2
        m_Curve:
        - serializedVersion: 3
          time: 0
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        - serializedVersion: 3
          time: 1
          value: 0
          inSlope: 0
          outSlope: 0
          tangentMode: 0
          weightedMode: 0
          inWeight: 0.33333334
          outWeight: 0.33333334
        m_PreInfinity: 2
        m_PostInfinity: 2
        m_RotationOrder: 4
    vectorLabel1_3: W
--- !u!4 &1052382919
Transform:
  m_ObjectHideFlags: 0
  m_CorrespondingSourceObject: {fileID: 0}
  m_PrefabInstance: {fileID: 0}
  m_PrefabAsset: {fileID: 0}
  m_GameObject: {fileID: 1052382916}
  serializedVersion: 2
  m_LocalRotation: {x: -0.52407336, y: -0.13719898, z: 0.26993656, w: 0.7960263}
  m_LocalPosition: {x: -50, y: 89.1, z: 15.3}
  m_LocalScale: {x: 1, y: 1, z: 1}
  m_ConstrainProportionsScale: 0
  m_Children: []
  m_Father: {fileID: 0}
  m_LocalEulerAnglesHint: {x: -130.511, y: 129.483, z: -118}
--- !u!1 &1113455181
GameObject:
  m_ObjectHideFlags: 0
  m_CorrespondingSourceObject: {fileID: 0}
  m_PrefabInstance: {fileID: 0}
  m_PrefabAsset: {fileID: 0}
  serializedVersion: 6
  m_Component:
  - component: {fileID: 1113455183}
  - component: {fileID: 1113455182}
  m_Layer: 0
  m_Name: Point Light (2)
  m_TagString: Untagged
  m_Icon: {fileID: 0}
  m_NavMeshLayer: 0
  m_StaticEditorFlags: 0
  m_IsActive: 1
--- !u!108 &1113455182
Light:
  m_ObjectHideFlags: 0
  m_CorrespondingSourceObject: {fileID: 0}
  m_PrefabInstance: {fileID: 0}
  m_PrefabAsset: {fileID: 0}
  m_GameObject: {fileID: 1113455181}
  m_Enabled: 1
  serializedVersion: 10
  m_Type: 2
  m_Shape: 0
  m_Color: {r: 1, g: 0.4411648, b: 0, a: 1}
  m_Intensity: 63
  m_Range: 17.1
  m_SpotAngle: 30
  m_InnerSpotAngle: 21.80208
  m_CookieSize: 10
  m_Shadows:
    m_Type: 0
    m_Resolution: -1
    m_CustomResolution: -1
    m_Strength: 1
    m_Bias: 0.05
    m_NormalBias: 0.4
    m_NearPlane: 0.2
    m_CullingMatrixOverride:
      e00: 1
      e01: 0
      e02: 0
      e03: 0
      e10: 0
      e11: 1
      e12: 0
      e13: 0
      e20: 0
      e21: 0
      e22: 1
      e23: 0
      e30: 0
      e31: 0
      e32: 0
      e33: 1
    m_UseCullingMatrixOverride: 0
  m_Cookie: {fileID: 0}
  m_DrawHalo: 0
  m_Flare: {fileID: 0}
  m_RenderMode: 0
  m_CullingMask:
    serializedVersion: 2
    m_Bits: 4294967295
  m_RenderingLayerMask: 1
  m_Lightmapping: 4
  m_LightShadowCasterMode: 0
  m_AreaSize: {x: 1, y: 1}
  m_BounceIntensity: 1
  m_ColorTemperature: 6570
  m_UseColorTemperature: 0
  m_BoundingSphereOverride: {x: 0, y: 0, z: 0, w: 0}
  m_UseBoundingSphereOverride: 0
  m_UseViewFrustumForShadowCasterCull: 1
  m_ShadowRadius: 0
  m_ShadowAngle: 0
--- !u!4 &1113455183
Transform:
  m_ObjectHideFlags: 0
  m_CorrespondingSourceObject: {fileID: 0}
  m_PrefabInstance: {fileID: 0}
  m_PrefabAsset: {fileID: 0}
  m_GameObject: {fileID: 1113455181}
  serializedVersion: 2
  m_LocalRotation: {x: 0, y: 0, z: 0, w: 1}
  m_LocalPosition: {x: -53.68, y: 84.95, z: 7.99}
  m_LocalScale: {x: 1, y: 1, z: 1}
  m_ConstrainProportionsScale: 0
  m_Children: []
  m_Father: {fileID: 0}
  m_LocalEulerAnglesHint: {x: 0, y: 0, z: 0}
--- !u!1 &2095062527
GameObject:
  m_ObjectHideFlags: 0
  m_CorrespondingSourceObject: {fileID: 0}
  m_PrefabInstance: {fileID: 0}
  m_PrefabAsset: {fileID: 0}
  serializedVersion: 6
  m_Component:
  - component: {fileID: 2095062529}
  - component: {fileID: 2095062528}
  m_Layer: 0
  m_Name: Point Light
  m_TagString: Untagged
  m_Icon: {fileID: 0}
  m_NavMeshLayer: 0
  m_StaticEditorFlags: 0
  m_IsActive: 1
--- !u!108 &2095062528
Light:
  m_ObjectHideFlags: 0
  m_CorrespondingSourceObject: {fileID: 0}
  m_PrefabInstance: {fileID: 0}
  m_PrefabAsset: {fileID: 0}
  m_GameObject: {fileID: 2095062527}
  m_Enabled: 1
  serializedVersion: 10
  m_Type: 2
  m_Shape: 0
  m_Color: {r: 1, g: 0.4411648, b: 0, a: 1}
  m_Intensity: 63
  m_Range: 17.1
  m_SpotAngle: 30
  m_InnerSpotAngle: 21.80208
  m_CookieSize: 10
  m_Shadows:
    m_Type: 0
    m_Resolution: -1
    m_CustomResolution: -1
    m_Strength: 1
    m_Bias: 0.05
    m_NormalBias: 0.4
    m_NearPlane: 0.2
    m_CullingMatrixOverride:
      e00: 1
      e01: 0
      e02: 0
      e03: 0
      e10: 0
      e11: 1
      e12: 0
      e13: 0
      e20: 0
      e21: 0
      e22: 1
      e23: 0
      e30: 0
      e31: 0
      e32: 0
      e33: 1
    m_UseCullingMatrixOverride: 0
  m_Cookie: {fileID: 0}
  m_DrawHalo: 0
  m_Flare: {fileID: 0}
  m_RenderMode: 0
  m_CullingMask:
    serializedVersion: 2
    m_Bits: 4294967295
  m_RenderingLayerMask: 1
  m_Lightmapping: 4
  m_LightShadowCasterMode: 0
  m_AreaSize: {x: 1, y: 1}
  m_BounceIntensity: 1
  m_ColorTemperature: 6570
  m_UseColorTemperature: 0
  m_BoundingSphereOverride: {x: 0, y: 0, z: 0, w: 0}
  m_UseBoundingSphereOverride: 0
  m_UseViewFrustumForShadowCasterCull: 1
  m_ShadowRadius: 0
  m_ShadowAngle: 0
--- !u!4 &2095062529
Transform:
  m_ObjectHideFlags: 0
  m_CorrespondingSourceObject: {fileID: 0}
  m_PrefabInstance: {fileID: 0}
  m_PrefabAsset: {fileID: 0}
  m_GameObject: {fileID: 2095062527}
  serializedVersion: 2
  m_LocalRotation: {x: 0, y: 0, z: 0, w: 1}
  m_LocalPosition: {x: -44.01, y: 88.81, z: 11.35}
  m_LocalScale: {x: 1, y: 1, z: 1}
  m_ConstrainProportionsScale: 0
  m_Children: []
  m_Father: {fileID: 0}
  m_LocalEulerAnglesHint: {x: 0, y: 0, z: 0}
--- !u!1660057539 &9223372036854775807
SceneRoots:
  m_ObjectHideFlags: 0
  m_Roots:
  - {fileID: 963194228}
  - {fileID: 705507995}
  - {fileID: 561899151}
  - {fileID: 1052382919}
  - {fileID: 842288767}
  - {fileID: 529940564}
  - {fileID: 2095062529}
  - {fileID: 854056116}
  - {fileID: 1113455183}
  - {fileID: 284065639}
