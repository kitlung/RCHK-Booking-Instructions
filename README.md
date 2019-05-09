# Facilitiy Booking System

_Comming Soon_ 

# Equipment Booking System

# Users' Instructions

# Admins' Instructions

## Main Page

![Screenshot](./images/mainPage.png)

    (1) : Side menu
    (2) : Selected tab
    (3) : Main screen

## Devices - Adding a new device

1. Press the add button

![Screenshot](./images/addDevice/addDevice_1.png)

2. Input all information inside the dialog

![Screenshot](./images/addDevice/addDevice_2.png)

__Quantity__ : Number of devices

__Available Quantity__ : Number of devices that are opened for booking.

**You cannot change the name of the device once you have clicked the _NEXT_ button.**

3. Upload images for the device.

![Screenshot](./images/addDevice/addDevice_3.png)

You must upload a cover image for the new device by clicking on the oarange box.

4. Choose a _Furthest Date_

Furthest Date is the maximum date that the device can be booked.

![Screenshot](./images/addDevice/addDevice_4.png)

You can uncheck the box if you don't need this setting.

![Screenshot](./images/addDevice/addDevice_5.png)

5. More settings.

![Screenshot](./images/addDevice/addDevice_6.png)

__Publish__ : Is the device opened to public or admins only?

![Screenshot](./images/addDevice/addDevice_7.png)

__Permission__ : Is the device opened to all users or staff only?

![Screenshot](./images/addDevice/addDevice_8.png)

__Resources Admin__ : Who can modify the device? Enter a valid weblogin ID. Use _comma_, _space_, _semicolon_ or _enter_ to separate IDs.

__Google Calendar__ : The calendar ID of google calendar.

6. Final checking

![Screenshot](./images/addDevice/addDevice_9.png)

## Device - Updating a device

1. General Information

![Screenshot](./images/editDevice/editDevice_1.png)

Click on the device that you want to modify

![Screenshot](./images/editDevice/editDevice_2.png)

Selected device's shadow is in orange colour.

![Screenshot](./images/editDevice/editDevice_3.png)

2. Photo

![Screenshot](./images/editDevice/editDevice_4.png)

When you click on one of these boxes, a small window pop up.

![Screenshot](./images/editDevice/editDevice_5.png)

_Upload_ : Upload new image.

_Browse Uploaded_ : Select image from all uploaded images.

It shows all uploaded images.

![Screenshot](./images/editDevice/editDevice_6.png)

Cover image can't be empty, which means you can't save it when you have selected the empty box.

![Screenshot](./images/editDevice/editDevice_7.png)

You can only delete a image when it is not displaying.

![Screenshot](./images/editDevice/editDevice_8.png)

3. Unit

Manage units of the device here.

![Screenshot](./images/editDevice/editDevice_9.png)

4. Admin Setting

![Screenshot](./images/editDevice/editDevice_10.png)

The only difference between this and the one in adding dialog is that you can only separate admin weblogin ID with _comma_ here.

5. Loan History

![Screenshot](./images/editDevice/editDevice_11.png)

You cannot change anything here. But you can check the record here.

6. Delete Device

![Screenshot](./images/editDevice/editDevice_12.png)

Think carefully before you delete a device. All related request will be deleted as well.

## Bundles - Adding a new bundle

1. Press the add button

![Screenshot](./images/addBundle/addBundle_1.png)

2. Input the name of the new bundle

![Screenshot](./images/addBundle/addBundle_2.png)

3. Select devices that will be included in this bundle

![Screenshot](./images/addBundle/addBundle_3.png)

4. Submit

![Screenshot](./images/addBundle/addBundle_4.png)

## Bundles - Editing a bundle

Click on the bundle that you want to modify

![Screenshot](./images/editBundle/editBundle_1.png)

Selected bundle's shadow is in orange colour.

1. General information

![Screenshot](./images/editBundle/editBundle_2.png)

2. Items

![Screenshot](./images/editBundle/editBundle_3.png)

Able to manage items inside this bundle.

3. Delete bundle

![Screenshot](./images/editBundle/editBundle_4.png)

Think carefully before you delete a bundle.

## Time setting

![Screenshot](./images/timeSetting.png)

You can mangage the pickup and return time here.

## Check in & out

![Screenshot](./images/checkInOut/checkInOut_1.png)

You can either input __Device Barcode__ or __Weblogin ID__

__Device Barcode__ : If you input device barcode first, you can :

1. Check in the device (if the device has been checked out)

![Screenshot](./images/checkInOut/checkInOut_2.png)

2. Get the status of the device (if the device is still available)

![Screenshot](./images/checkInOut/checkInOut_3.png)

__Weblogin ID__ : If you input Weblogin ID first, you can :

1. Get user's information

![Screenshot](./images/checkInOut/checkInOut_4.png)

__Loan History__ : The checkout and checkin list of that user

![Screenshot](./images/checkInOut/checkInOut_6.png)

__Reservation__ : All information of requests made by that user 

![Screenshot](./images/checkInOut/checkInOut_5.png)

The status is in green colour if user return the device in time; while it is in red colour if user return the device after the due date.

__Clear__ : Use this when you want to deal with another user

__Weblogin ID -> Barcode__ : Checkout an item

![Screenshot](./images/checkInOut/checkInOut_7.png)

__Weblogin ID -> Weblogin ID__ : Nothing Happen

__Record Table__

Able to check all records here

![Screenshot](./images/checkInOut/checkInOut_8.png)

__Loan__ : All check out records

Click on the hourglass icon to extend user's request.

![Screenshot](./images/checkInOut/checkInOut_9.png)

Input new return due date and time inside the dialog.

_Note that it only extend one item but not the whole request._

__Return__ : All check in records

__All__ : Both records

## Pending List

### Pending List

![Screenshot](./images/pendingList/pendingList_1.png)

Manage pending request here.

You can either approve here or through [email](#email).

### In Progress

Showing all approved requests

You can cancel an approved request but you cannout cancel it once the device is checked out.

![Screenshot](./images/pendingList/pendingList_2.png)

^ _Approved_

![Screenshot](./images/pendingList/pendingList_3.png)

^ _Checked out_ / _Extended_

### Completed

![Screenshot](./images/pendingList/pendingList_4.png)

There is a dropdown list below the table. Use this to filter records according to the pickup date.

![Screenshot](./images/pendingList/pendingList_5.png)

## Admin Reserve

If you are the admin of a device, you can reserve that device without approving. It will automatically add an event to your google calendar as well.

![Screenshot](./images/reserve/reserve_1.png)

^ Not admin

![Screenshot](./images/reserve/reserve_2.png)

^ Shows device only if you are admin of it

This reserve function is designed for ad hoc checkout so you won't have to input pick up date and time.

## Email

### User Receipt

![Screenshot](./images/email/email_1.png)

When user request some devices, they will receive a receipt.

### Admin Pending

When user request a device, admin of that device will receive an email.

![Screenshot](./images/email/email_2.png)

Admin can approve / decline the request through the email.

Nothing happens if you have already approved the request but click on the _Approve_ button again.

### User Approved / Declined

![Screenshot](./images/email/email_3.png)

User will receive an email if admin approve / decline their request.

### User Cancel Approved

![Screenshot](./images/email/email_4.png)

Admin will receive an email if user cancel an approved request.

### User Cancel Pending

![Screenshot](./images/email/email_5.png)

User will receive an email if he/she cancel a pending request.

### User Admin Cancel

![Screenshot](./images/email/email_6.png)

User will receive an email if admin cancel his/her request

### User Late

![Screenshot](./images/email/email_7.png)

User will receive an email every 9 am in the morning if he/she hasn't return the device after due date.

### User didn't Pick up all items

![Screenshot](./images/email/email_8.png)

User will receive an email every 7 am if he/she hasn't pick up all requested items.
