# HTML, advanced

![Complete web page](https://s3.eu-west-3.amazonaws.com/hbtn.intranet/uploads/medias/2021/4/1f4cd63ecc3a8c03b0f4309b74aca179e225aabf.jpg?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIA4MYA5JM5DUTZGMZG%2F20240115%2Feu-west-3%2Fs3%2Faws4_request&X-Amz-Date=20240115T162714Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=d42c8825589fb07d6e3ea4691ce2589c99741defe612c872d082b0bc372c6ce8)
![wireframe](https://s3.eu-west-3.amazonaws.com/hbtn.intranet/uploads/medias/2021/4/97c8976d2ff5ff1871d7a0815b72773379df6acb.jpg?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIA4MYA5JM5DUTZGMZG%2F20240115%2Feu-west-3%2Fs3%2Faws4_request&X-Amz-Date=20240115T162714Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=f01262ce089c4cb182ef53271850c036a77d64898fc1c29d22eb1144958cbb0c)

## Purpose

Learning the base elements of HTML, the concept of wireframing, and to familiarize ourselfs with figma.

## Goal

Recreate the HTML for the provided figma page

## Tasks

#### 0. README and objectives!

Familiarize your self with figma, how to use some tools to extract html elements from the completed webpage, and create this README.md file.

#### 1. Header
Let’s start by the top: the header

Here the wireframe of it:

![Header wireframe](https://s3.eu-west-3.amazonaws.com/hbtn.intranet/uploads/medias/2021/4/415b0226fd338ff76a330b371fc83c9224254c47.jpg?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIA4MYA5JM5DUTZGMZG%2F20240115%2Feu-west-3%2Fs3%2Faws4_request&X-Amz-Date=20240115T162714Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=2fc56b9293debe96d5bcb556e937f00768b28846953e5cb4b8e7436e8c0cf1c4)

+ Create the HTML skeleton (html, head, body, etc.)
+ In the body, add an header tag
+ Inside this header:
    + Add a link element with an image inside
    + Add a block of 3 link elements

#### 2. Banner
Now, the banner under the header:

![Banner wireframe](https://s3.eu-west-3.amazonaws.com/hbtn.intranet/uploads/medias/2021/4/ee07503a513036f49d73b31df339ee798f9f277f.jpg?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIA4MYA5JM5DUTZGMZG%2F20240115%2Feu-west-3%2Fs3%2Faws4_request&X-Amz-Date=20240115T162714Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=9d383056287f27632ddcbf69befbcb55cdc76f8f3dd88a59e0a61c005508f2e8)

Under the header, add a main element with inside a section element.

In this section element, add:
+ A block with inside:
    + An heading tag (don’t forget to use the correct heading value)
    + A text element
    + A button tag
+ Another block with inside:
    + Another heading tag (same, be careful about which one you are using)
    + A block containing 4 blocks - each block with inside:
        + An image
        + An heading tag
        + A text

#### 3. Quote
Under the banner, we will add the quote block:

![quote wireframe](https://s3.eu-west-3.amazonaws.com/hbtn.intranet/uploads/medias/2021/4/25b4264f9266962bffb39791b265317cc5ff8147.jpg?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIA4MYA5JM5DUTZGMZG%2F20240115%2Feu-west-3%2Fs3%2Faws4_request&X-Amz-Date=20240115T162714Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=b2b3c4ef46401330ee29f84f6d561c481cfd905b969f0f0f70ba2f7ecfe98da1)

The quote section is inside the main:
+ Create a new section for the quote 
+ Inside, add a block containing:
    + An image
    + Another block with inside:
        + A quote tag
        + An author quote
        + A text

#### 4. Videos
Let’s now add the videos list:

![video wireframe](https://s3.eu-west-3.amazonaws.com/hbtn.intranet/uploads/medias/2021/4/a5712ac70330c6812c6aee2bf21efe7ac53d1397.jpg?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIA4MYA5JM5DUTZGMZG%2F20240115%2Feu-west-3%2Fs3%2Faws4_request&X-Amz-Date=20240115T162714Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=413a13f221fd5f7ec6b541009073d2dd4ab6e9c0c225a9c6c32f28e541973e30)

New section with inside:
+ An heading tag
+ A block containing the 4 video block - each of them are composed with:
    + An image
    + An heading
    + A text
    + A block for the author:
        + A image
        + An heading
    + A block for the rating:
        + A block of images (one star = one image)
        + A text

#### 5. Membership
Membership section is similar as the videos list:

![membership wireframe](https://s3.eu-west-3.amazonaws.com/hbtn.intranet/uploads/medias/2021/4/1ddf18bc6d89725de2fde4881e8990fae6d89628.jpg?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIA4MYA5JM5DUTZGMZG%2F20240115%2Feu-west-3%2Fs3%2Faws4_request&X-Amz-Date=20240115T162714Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=54ac4c3c6cb5fe573063ce498addd4ca3238b050a1763f8c4af88a483e3db698)

After the videos list section, add a new section containing:
+ An heading
+ A block with inside 4 block item - each block defined with:
    + An image
    + An heading
    + A text
+ A button

#### 6. FAQ
The FAQ section is ending the page before the footer:

![F.A.Q wireframe](https://s3.eu-west-3.amazonaws.com/hbtn.intranet/uploads/medias/2021/4/e4b2806abe9edc126fa0d4155aaf5d7e7da479e4.jpg?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIA4MYA5JM5DUTZGMZG%2F20240115%2Feu-west-3%2Fs3%2Faws4_request&X-Amz-Date=20240115T162714Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=ad7f5a217574377a8518f62c3c60f9846440ed65fe5be9e0b63cef01c93bd0bd)

Add a section for the FAQ with inside:
+ A block that contains 2 “row block”
+ Each “row block” contains 2 “item block”
+ Each “item block” is composed of:
    + An heading
    + A text

#### 7. Footer
And… the footer!

![footer wireframe](https://s3.eu-west-3.amazonaws.com/hbtn.intranet/uploads/medias/2021/4/7224527ac842981b3b387cd9d713b4a1b912a487.jpg?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIA4MYA5JM5DUTZGMZG%2F20240115%2Feu-west-3%2Fs3%2Faws4_request&X-Amz-Date=20240115T162714Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=8f30537c3e61ed2da57ee02f1427825cfc55fafd0f09a000e54d7212714d716a)

After the last section, outside of the main, add a footer:
+ After the last section, outside of the main, add a footer:
    + A “row block” with:
        + An image
        + A block with inside:
            + Images with link
    + A text