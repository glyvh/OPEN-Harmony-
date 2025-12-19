# OPEN-Harmony-
这是我的作业
{
  "app": {
    "signingConfigs": [
      {
        "name": "default",
        "material": {
          "certpath": "C:/Users/gly vrhs/.ohos/config/openharmony/default_gly_Yllg1SlY30UrHNaiJCmLLmuAXB1XlU8cKkYnpEyKbZM=.cer",
          "storePassword": "0000001AF9D606398877227CC9C918620FD8B0CBD09700D05934813D891FCF60DDF9E77261844A1A512E",
          "keyAlias": "debugKey",
          "keyPassword": "0000001A25DBA7917FCE74DFB0346A410238C6551EE677D96F537026C080CB8F2B78FAED53DF21E528E5",
          "profile": "C:/Users/gly vrhs/.ohos/config/openharmony/default_gly_Yllg1SlY30UrHNaiJCmLLmuAXB1XlU8cKkYnpEyKbZM=.p7b",
          "signAlg": "SHA256withECDSA",
          "storeFile": "C:/Users/gly vrhs/.ohos/config/openharmony/default_gly_Yllg1SlY30UrHNaiJCmLLmuAXB1XlU8cKkYnpEyKbZM=.p12"
        }
      }
    ],
    "products": [
      {
        "name": "default",
        "signingConfig": "default",
        "compileSdkVersion": 12,
        "compatibleSdkVersion": 12,
        "runtimeOS": "OpenHarmony",
        "buildOption": {
          "strictMode": {
            "caseSensitiveCheck": true,
            "useNormalizedOHMUrl": true
          }
        }
      }
    ],
    "buildModeSet": [
      {
        "name": "debug",
      },
      {
        "name": "release"
      }
    ]
  },
  "modules": [
    {
      "name": "entry",
      "srcPath": "./entry",
      "targets": [
        {
          "name": "default",
          "applyToProducts": [
            "default"
          ]
        }
      ]
    }
  ]
}
