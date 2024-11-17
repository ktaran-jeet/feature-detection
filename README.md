# feature-detection
Feature detection and matching is an important task in many computer vision applications, such as structure-from-motion, image retrieval, object detection, and more.


Main Components Of Feature Detection And Matching
1.Detection: Identify the Interest Point
2.Description: The local appearance around each feature point is described in some way that is (ideally) invariant under changes in illumination, translation, scale, and in-plane rotation. We typically end up with a descriptor vector for each feature point.
3.Matching: Descriptors are compared across the images, to identify similar features. For two images we may get a set of pairs (Xi, Yi) ↔ (Xi, Yi), where (Xi, Yi) is a feature in one image and (Xi, Yi) its matching feature in the other image.

