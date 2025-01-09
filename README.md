# Recipes for AGP version `8.7`
This branch contains recipes compatible with AGP 8.7. If you want to find recipes
for other AGP versions, switch to the corresponding `agp-*` branch.

This branch is read only. Contributions are only accepted on the `studio-main` branch. See `CONTRIBUTION.md`
there.
# Recipes Index
Index is organized in categories, offering different ways to reach the recipe you want.
## Themes
* Android Assets - [addGeneratedSourceFolder](addGeneratedSourceFolder), [legacyTaskBridging](legacyTaskBridging)
* Android Manifest - [createSingleArtifact](createSingleArtifact), [transformManifest](transformManifest), [perVariantManifestPlaceholder](perVariantManifestPlaceholder)
* Artifact API - [addMultipleArtifact](addMultipleArtifact), [transformDirectory](transformDirectory), [transformMultiple](transformMultiple), [createSingleArtifact](createSingleArtifact), [listenToMultipleArtifact](listenToMultipleArtifact), [listenToArtifacts](listenToArtifacts), [getSingleArtifact](getSingleArtifact), [workerEnabledTransformation](workerEnabledTransformation), [getScopedArtifacts](getScopedArtifacts), [transformAllClasses](transformAllClasses), [appendToScopedArtifacts](appendToScopedArtifacts), [appendToMultipleArtifact](appendToMultipleArtifact), [transformManifest](transformManifest), [getMultipleArtifact](getMultipleArtifact)
* DSL - [extendingAgp](extendingAgp), [addBuildTypeUsingDslFinalize](addBuildTypeUsingDslFinalize)
* Dependency Resolution - [variantDependencySubstitutionTest](variantDependencySubstitutionTest)
* Sources - [addGeneratedSourceFolder](addGeneratedSourceFolder), [addCustomSourceType](addCustomSourceType), [legacyTaskBridging](legacyTaskBridging)
## Plugin Features
* TestFixtures - [testFixtures](testFixtures)
## APIs
* AndroidComponentsExtension.beforeVariants() - [disableTests](disableTests), [selectVariants](selectVariants)
* AndroidComponentsExtension.onVariants() - [addMultipleArtifact](addMultipleArtifact), [transformDirectory](transformDirectory), [addGeneratedSourceFolder](addGeneratedSourceFolder), [extendingAgp](extendingAgp), [transformMultiple](transformMultiple), [variantOutput](variantOutput), [registerPreBuild](registerPreBuild), [createSingleArtifact](createSingleArtifact), [variantDependencySubstitutionTest](variantDependencySubstitutionTest), [addCustomSourceType](addCustomSourceType), [listenToMultipleArtifact](listenToMultipleArtifact), [listenToArtifacts](listenToArtifacts), [disableTests](disableTests), [getSingleArtifact](getSingleArtifact), [workerEnabledTransformation](workerEnabledTransformation), [getScopedArtifacts](getScopedArtifacts), [transformAllClasses](transformAllClasses), [legacyTaskBridging](legacyTaskBridging), [onVariants](onVariants), [appendToScopedArtifacts](appendToScopedArtifacts), [appendToMultipleArtifact](appendToMultipleArtifact), [transformManifest](transformManifest), [addCustomBuildConfigFields](addCustomBuildConfigFields), [getMultipleArtifact](getMultipleArtifact), [asmTransformClasses](asmTransformClasses), [allProjectsApkAction](allProjectsApkAction), [perVariantManifestPlaceholder](perVariantManifestPlaceholder)
* AndroidComponentsExtension.registerExtension() - [extendingAgp](extendingAgp)
* AndroidComponentsExtension.selector() - [variantOutput](variantOutput), [allProjectsApkAction](allProjectsApkAction), [selectVariants](selectVariants)
* ApplicationVariant.applicationId - [onVariants](onVariants)
* ApplicationVariant.outputs - [variantOutput](variantOutput)
* Artifact.ContainsMany - [listenToArtifacts](listenToArtifacts)
* ArtifactTransformationRequest - [workerEnabledTransformation](workerEnabledTransformation)
* Artifacts.add() - [addMultipleArtifact](addMultipleArtifact), [transformMultiple](transformMultiple)
* Artifacts.forScope() - [getScopedArtifacts](getScopedArtifacts), [transformAllClasses](transformAllClasses), [appendToScopedArtifacts](appendToScopedArtifacts)
* Artifacts.get() - [addMultipleArtifact](addMultipleArtifact), [transformDirectory](transformDirectory), [addGeneratedSourceFolder](addGeneratedSourceFolder), [transformMultiple](transformMultiple), [variantOutput](variantOutput), [getSingleArtifact](getSingleArtifact), [legacyTaskBridging](legacyTaskBridging), [appendToMultipleArtifact](appendToMultipleArtifact), [transformManifest](transformManifest), [allProjectsApkAction](allProjectsApkAction), [perVariantManifestPlaceholder](perVariantManifestPlaceholder)
* Artifacts.getAll() - [getMultipleArtifact](getMultipleArtifact)
* Artifacts.use() - [transformDirectory](transformDirectory), [transformMultiple](transformMultiple), [createSingleArtifact](createSingleArtifact), [listenToMultipleArtifact](listenToMultipleArtifact), [listenToArtifacts](listenToArtifacts), [workerEnabledTransformation](workerEnabledTransformation), [appendToMultipleArtifact](appendToMultipleArtifact), [transformManifest](transformManifest)
* BuildConfigField() - [addCustomBuildConfigFields](addCustomBuildConfigFields)
* BuiltArtifact - [workerEnabledTransformation](workerEnabledTransformation)
* BuiltArtifact.versionCode - [listenToArtifacts](listenToArtifacts)
* BuiltArtifact.versionName - [listenToArtifacts](listenToArtifacts)
* BuiltArtifacts.elements - [listenToArtifacts](listenToArtifacts)
* BuiltArtifacts.variantName - [listenToArtifacts](listenToArtifacts)
* BuiltArtifactsLoader.load() - [listenToArtifacts](listenToArtifacts)
* CanMinifyAndroidResourcesBuilder.shrinkResources - [selectVariants](selectVariants)
* CanMinifyCodeBuilder.isMinifyEnabled - [selectVariants](selectVariants)
* CombiningOperationRequest.toTransform() - [transformMultiple](transformMultiple)
* Component.artifacts - [addMultipleArtifact](addMultipleArtifact), [transformDirectory](transformDirectory), [addGeneratedSourceFolder](addGeneratedSourceFolder), [transformMultiple](transformMultiple), [variantOutput](variantOutput), [createSingleArtifact](createSingleArtifact), [getScopedArtifacts](getScopedArtifacts), [legacyTaskBridging](legacyTaskBridging), [appendToScopedArtifacts](appendToScopedArtifacts), [appendToMultipleArtifact](appendToMultipleArtifact), [transformManifest](transformManifest), [getMultipleArtifact](getMultipleArtifact)
* Component.compileConfiguration - [variantDependencySubstitutionTest](variantDependencySubstitutionTest)
* Component.runtimeConfiguration - [variantDependencySubstitutionTest](variantDependencySubstitutionTest)
* Component.sources - [addGeneratedSourceFolder](addGeneratedSourceFolder), [addCustomSourceType](addCustomSourceType), [legacyTaskBridging](legacyTaskBridging)
* Configuration.resolutionStrategy - [variantDependencySubstitutionTest](variantDependencySubstitutionTest)
* DslExtension.Builder.build() - [extendingAgp](extendingAgp)
* DslExtension.Builder.extendBuildTypeWith() - [extendingAgp](extendingAgp)
* DslExtension.Builder.extendProductFlavorWith() - [extendingAgp](extendingAgp)
* DslExtension.Builder.extendProjectWith() - [extendingAgp](extendingAgp)
* DslLifecycle.finalizeDsl() - [addBuildTypeUsingDslFinalize](addBuildTypeUsingDslFinalize)
* GeneratesApk.applicationId - [onVariants](onVariants)
* Gradle.beforeProject() - [allProjectsApkAction](allProjectsApkAction)
* HasDeviceTests.deviceTests - [disableTests](disableTests)
* HasDeviceTestsBuilder.deviceTests - [disableTests](disableTests)
* HasHostTests.hostTests - [disableTests](disableTests)
* HasHostTestsBuilder.hostTests - [disableTests](disableTests)
* HasUnitTestBuilder.enableUnitTest - [selectVariants](selectVariants)
* InAndOutDirectoryOperationRequest.toTransform() - [transformDirectory](transformDirectory)
* InAndOutDirectoryOperationRequest.toTransformMany() - [workerEnabledTransformation](workerEnabledTransformation)
* InAndOutFileOperationRequest.toTransform() - [transformManifest](transformManifest)
* Instrumentation.transformClassesWith() - [asmTransformClasses](asmTransformClasses)
* LifeCycleTasks.registerPreBuild() - [registerPreBuild](registerPreBuild)
* MapProperty.put() - [addCustomBuildConfigFields](addCustomBuildConfigFields), [perVariantManifestPlaceholder](perVariantManifestPlaceholder)
* MultipleArtifact.MULTIDEX_KEEP_PROGUARD - [getMultipleArtifact](getMultipleArtifact)
* MultipleArtifact.NATIVE_DEBUG_METADATA - [addMultipleArtifact](addMultipleArtifact), [transformMultiple](transformMultiple), [listenToMultipleArtifact](listenToMultipleArtifact), [appendToMultipleArtifact](appendToMultipleArtifact)
* MultipleArtifactTypeOutOperationRequest.toListenTo() - [listenToMultipleArtifact](listenToMultipleArtifact)
* OutOperationRequest.toAppendTo() - [appendToMultipleArtifact](appendToMultipleArtifact)
* OutOperationRequest.toCreate() - [createSingleArtifact](createSingleArtifact)
* OutOperationRequest.toListenTo() - [listenToArtifacts](listenToArtifacts)
* Plugin<Settings> - [allProjectsApkAction](allProjectsApkAction)
* ResolutionStrategy.dependencySubstitution() - [variantDependencySubstitutionTest](variantDependencySubstitutionTest)
* ScopedArtifact.CLASSES - [getScopedArtifacts](getScopedArtifacts), [transformAllClasses](transformAllClasses), [appendToScopedArtifacts](appendToScopedArtifacts), [asmTransformClasses](asmTransformClasses)
* ScopedArtifacts.Scope.ALL - [getScopedArtifacts](getScopedArtifacts), [appendToScopedArtifacts](appendToScopedArtifacts)
* ScopedArtifacts.Scope.PROJECT - [getScopedArtifacts](getScopedArtifacts), [transformAllClasses](transformAllClasses), [appendToScopedArtifacts](appendToScopedArtifacts), [asmTransformClasses](asmTransformClasses)
* ScopedArtifacts.use() - [getScopedArtifacts](getScopedArtifacts), [transformAllClasses](transformAllClasses), [appendToScopedArtifacts](appendToScopedArtifacts), [asmTransformClasses](asmTransformClasses)
* ScopedArtifactsOperation.toAppend() - [appendToScopedArtifacts](appendToScopedArtifacts)
* ScopedArtifactsOperation.toGet() - [getScopedArtifacts](getScopedArtifacts), [appendToScopedArtifacts](appendToScopedArtifacts), [asmTransformClasses](asmTransformClasses)
* ScopedArtifactsOperation.toTransform() - [transformAllClasses](transformAllClasses)
* SingleArtifact.APK - [listenToArtifacts](listenToArtifacts), [workerEnabledTransformation](workerEnabledTransformation), [allProjectsApkAction](allProjectsApkAction)
* SingleArtifact.ASSETS - [transformDirectory](transformDirectory), [addGeneratedSourceFolder](addGeneratedSourceFolder), [legacyTaskBridging](legacyTaskBridging)
* SingleArtifact.BUNDLE - [addMultipleArtifact](addMultipleArtifact), [getSingleArtifact](getSingleArtifact), [appendToMultipleArtifact](appendToMultipleArtifact)
* SingleArtifact.MERGED_MANIFEST - [variantOutput](variantOutput), [createSingleArtifact](createSingleArtifact), [transformManifest](transformManifest), [perVariantManifestPlaceholder](perVariantManifestPlaceholder)
* SourceDirectories.addGeneratedSourceDirectory() - [addGeneratedSourceFolder](addGeneratedSourceFolder), [addCustomSourceType](addCustomSourceType), [legacyTaskBridging](legacyTaskBridging)
* SourceDirectories.addStaticSourceDirectory() - [addCustomSourceType](addCustomSourceType)
* TaskBasedOperation.wiredWith() - [transformMultiple](transformMultiple), [createSingleArtifact](createSingleArtifact), [listenToArtifacts](listenToArtifacts)
* TaskBasedOperation.wiredWithDirectories() - [transformDirectory](transformDirectory), [workerEnabledTransformation](workerEnabledTransformation)
* TaskBasedOperation.wiredWithFiles() - [transformManifest](transformManifest)
* TaskBasedOperation.wiredWithMultiple() - [listenToMultipleArtifact](listenToMultipleArtifact)
* TaskOutputs.upToDateWhen() - [transformManifest](transformManifest)
* TaskProvider.flatMap() - [createSingleArtifact](createSingleArtifact)
* TaskProvider.map() - [addCustomBuildConfigFields](addCustomBuildConfigFields)
* Variant.buildConfigFields - [addCustomBuildConfigFields](addCustomBuildConfigFields)
* Variant.components - [variantDependencySubstitutionTest](variantDependencySubstitutionTest)
* Variant.manifestPlaceholders - [perVariantManifestPlaceholder](perVariantManifestPlaceholder)
* Variant.nestedComponents - [variantDependencySubstitutionTest](variantDependencySubstitutionTest)
* VariantBuilder.minSdk - [selectVariants](selectVariants)
* VariantExtensionConfig - [extendingAgp](extendingAgp)
* VariantOutputConfiguration.OutputType.SINGLE - [variantOutput](variantOutput)
* VariantOutputConfiguration.outputType - [variantOutput](variantOutput)
* VariantSelector.all() - [variantOutput](variantOutput), [selectVariants](selectVariants)
* VariantSelector.withBuildType() - [variantDependencySubstitutionTest](variantDependencySubstitutionTest), [allProjectsApkAction](allProjectsApkAction), [selectVariants](selectVariants)
* VariantSelector.withFlavor() - [variantOutput](variantOutput), [selectVariants](selectVariants)
* VariantSelector.withName() - [selectVariants](selectVariants)
* task.getOutputs() - [transformManifest](transformManifest)
## Call chains
* DslExtension.Builder().extendProjectWith().extendBuildTypeWith().extendProductFlavorWith().build() - [extendingAgp](extendingAgp)
* HasDeviceTests.deviceTests.get() - [disableTests](disableTests)
* HasDeviceTestsBuilder.deviceTests.get().enable - [disableTests](disableTests)
* HasHostTests.hostTests.get() - [disableTests](disableTests)
* HasHostTestsBuilder.hostTests.get().enable - [disableTests](disableTests)
* androidComponents.beforeVariants {} - [disableTests](disableTests), [selectVariants](selectVariants)
* androidComponents.finalizeDsl {} - [addBuildTypeUsingDslFinalize](addBuildTypeUsingDslFinalize)
* androidComponents.onVariants {} - [addMultipleArtifact](addMultipleArtifact), [transformDirectory](transformDirectory), [addGeneratedSourceFolder](addGeneratedSourceFolder), [extendingAgp](extendingAgp), [transformMultiple](transformMultiple), [variantOutput](variantOutput), [registerPreBuild](registerPreBuild), [createSingleArtifact](createSingleArtifact), [variantDependencySubstitutionTest](variantDependencySubstitutionTest), [addCustomSourceType](addCustomSourceType), [listenToMultipleArtifact](listenToMultipleArtifact), [listenToArtifacts](listenToArtifacts), [disableTests](disableTests), [getSingleArtifact](getSingleArtifact), [workerEnabledTransformation](workerEnabledTransformation), [getScopedArtifacts](getScopedArtifacts), [transformAllClasses](transformAllClasses), [legacyTaskBridging](legacyTaskBridging), [onVariants](onVariants), [appendToScopedArtifacts](appendToScopedArtifacts), [appendToMultipleArtifact](appendToMultipleArtifact), [transformManifest](transformManifest), [addCustomBuildConfigFields](addCustomBuildConfigFields), [getMultipleArtifact](getMultipleArtifact), [asmTransformClasses](asmTransformClasses), [allProjectsApkAction](allProjectsApkAction), [perVariantManifestPlaceholder](perVariantManifestPlaceholder)
* androidComponents.registerExtension() - [extendingAgp](extendingAgp)
* androidComponents.selector().all() - [variantOutput](variantOutput), [selectVariants](selectVariants)
* androidComponents.selector().withBuildType() - [variantDependencySubstitutionTest](variantDependencySubstitutionTest), [allProjectsApkAction](allProjectsApkAction), [selectVariants](selectVariants)
* androidComponents.selector().withFlavor() - [variantOutput](variantOutput), [selectVariants](selectVariants)
* androidComponents.selector().withName() - [selectVariants](selectVariants)
* configuration.resolutionStrategy.dependencySubstitution {} - [variantDependencySubstitutionTest](variantDependencySubstitutionTest)
* settings.gradle.beforeProject {} - [allProjectsApkAction](allProjectsApkAction)
* substitute().using() - [variantDependencySubstitutionTest](variantDependencySubstitutionTest)
* task.outputs.upToDateWhen {} - [transformManifest](transformManifest)
* transformationRequest.submit() - [workerEnabledTransformation](workerEnabledTransformation)
* variant.applicationId - [onVariants](onVariants)
* variant.artifacts.add() - [addMultipleArtifact](addMultipleArtifact), [transformMultiple](transformMultiple)
* variant.artifacts.forScope().use().toAppend() - [appendToScopedArtifacts](appendToScopedArtifacts)
* variant.artifacts.forScope().use().toGet() - [getScopedArtifacts](getScopedArtifacts), [asmTransformClasses](asmTransformClasses)
* variant.artifacts.forScope().use().toTransform() - [transformAllClasses](transformAllClasses)
* variant.artifacts.get() - [addMultipleArtifact](addMultipleArtifact), [transformDirectory](transformDirectory), [addGeneratedSourceFolder](addGeneratedSourceFolder), [transformMultiple](transformMultiple), [variantOutput](variantOutput), [getSingleArtifact](getSingleArtifact), [legacyTaskBridging](legacyTaskBridging), [appendToMultipleArtifact](appendToMultipleArtifact), [transformManifest](transformManifest), [asmTransformClasses](asmTransformClasses), [allProjectsApkAction](allProjectsApkAction), [perVariantManifestPlaceholder](perVariantManifestPlaceholder)
* variant.artifacts.getAll() - [getMultipleArtifact](getMultipleArtifact)
* variant.artifacts.use().wiredWith().toAppendTo() - [appendToMultipleArtifact](appendToMultipleArtifact)
* variant.artifacts.use().wiredWith().toCreate() - [createSingleArtifact](createSingleArtifact)
* variant.artifacts.use().wiredWith().toListenTo() - [listenToMultipleArtifact](listenToMultipleArtifact), [listenToArtifacts](listenToArtifacts)
* variant.artifacts.use().wiredWith().toTransform() - [transformMultiple](transformMultiple)
* variant.artifacts.use().wiredWithDirectories().toTransform() - [transformDirectory](transformDirectory)
* variant.artifacts.use().wiredWithDirectories().toTransformMany() - [workerEnabledTransformation](workerEnabledTransformation)
* variant.artifacts.use().wiredWithFiles().toTransform() - [transformManifest](transformManifest)
* variant.buildConfigFields.put() - [addCustomBuildConfigFields](addCustomBuildConfigFields)
* variant.instrumentation.transformClassesWith() - [asmTransformClasses](asmTransformClasses)
* variant.manifestPlaceholders.put() - [perVariantManifestPlaceholder](perVariantManifestPlaceholder)
* variant.registerPreBuild() - [registerPreBuild](registerPreBuild)
* variant.sources.*.addGeneratedSourceDirectory() - [addGeneratedSourceFolder](addGeneratedSourceFolder), [addCustomSourceType](addCustomSourceType), [legacyTaskBridging](legacyTaskBridging)
* variant.sources.*.addStaticSourceDirectory() - [addCustomSourceType](addCustomSourceType)
* variant.sources.*.all - [addGeneratedSourceFolder](addGeneratedSourceFolder), [addCustomSourceType](addCustomSourceType)
## Others
* All projects - [allProjectsApkAction](allProjectsApkAction)
* DeviceTestBuilder.ANDROID_TEST_TYPE - [disableTests](disableTests)
* Extending AGP DSL - [extendingAgp](extendingAgp)
* HostTestBuilder.UNIT_TEST_TYPE - [disableTests](disableTests)
* Legacy API bridging - [legacyTaskBridging](legacyTaskBridging)
* Placeholders - [perVariantManifestPlaceholder](perVariantManifestPlaceholder)
* Renaming APKs - [listenToArtifacts](listenToArtifacts)
* SourceDirectories.Flat - [addCustomSourceType](addCustomSourceType)
* SourceDirectories.Layered - [addGeneratedSourceFolder](addGeneratedSourceFolder)
* SourceDirectories.add - [addCustomSourceType](addCustomSourceType)
* registerSourceType - [addCustomSourceType](addCustomSourceType)
# License
```
Copyright 2022 The Android Open Source Project

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    https://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
```
