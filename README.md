# image_optimization
Image optimization using lambda@edge and cloudfront.

# resources
https://aws.amazon.com/jp/blogs/networking-and-content-delivery/resizing-images-with-amazon-cloudfront-lambdaedge-aws-cdn-blog/

# initial problems and solutions
- didn't name the lambda function node.js files as index.js the first time zipping, error upon accessing url.

# Tasks
- this version only supports image resizing, so would want to add in image optimization features using imagemagick. Since imagemagick is already included in the node.js application in lambda, this should be fairly easy.
