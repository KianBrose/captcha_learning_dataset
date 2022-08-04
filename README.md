# Kian's Captcha Learning Dataset
Hello! I have created this dataset that consists of captcha png's and their **SHA-1** solutions within the name of the image to help people that want to learn AI have an interesting "challenge" to solve.

I might add more captcha types with their solutions in the future

## Available datasets
| Dataset folder | Amount of images | Type |
|--|--|--|
| captcha/ | 17962 | 1 |

## How to "validate" a solution by type

### Type 1
This dataset has captcha png's with the file naming in this format:
`cap_sha1.png`, so the file `cap_0004cd3f56246ad7396b8509455cad4bc860dbae.png` would have a solution that when hashed as **SHA-1** returns `0004cd3f56246ad7396b8509455cad4bc860dbae`

For example, here is [cap_0004cd3f56246ad7396b8509455cad4bc860dbae.png](https://kianbrose.com/assets/files/2022-08-04/1659637656-555527-cap-0004cd3f56246ad7396b8509455cad4bc860dbae.png)

![Captcha example image](https://kianbrose.com/assets/files/2022-08-04/1659637656-555527-cap-0004cd3f56246ad7396b8509455cad4bc860dbae.png)

When solved manually, the answer is **2ra15**

The SHA-1 hash for this image as stated in the name is **0004cd3f56246ad7396b8509455cad4bc860dbae**

Trying to convert the answer to SHA-1 using either code or in this example [this website](http://www.sha1-online.com/):
![SHA1 solution](https://kianbrose.com/assets/files/2022-08-04/1659638029-514822-solvecap.png)You can see that the solution's SHA-1 matches with the captcha's filename
