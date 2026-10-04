BK PURE FOODS | STATIC WEBSITE

অর্ডার পাঠানোর ব্যবস্থা আগে থেকেই বসানো আছে। BK Nexus enquiry form-এর মতো FormSubmit দিয়ে bknexusltd@gmail.com-এ details পাঠানো হবে। Code/token বসাতে হবে না।

1. ZIP extract করে সব ফাইল GitHub repository-এর root-এ আপলোড করুন।
2. Cloudflare Pages-এ repository connect করুন। Framework: None। Build command ফাঁকা। Output directory: / (repository root)।
3. Live website থেকে একটি test order দিন। Inbox ও Spam folder দেখুন। FormSubmit activation email এলে একবার Confirm করুন এবং আবার test order দিন। আগে থেকেই activated থাকলে এই ধাপ প্রয়োজন নাও হতে পারে। এটি FormSubmit-এর নিয়ম, website code দিয়ে bypass করা যায় না।

Cloudflare email, Worker, database, Secret, npm বা build setup দরকার নেই। Customer WhatsApp বা email লাগবে না। Order details পাঠানোর সময় কোনো mail app খুলবে না।

ওয়েবসাইটের স্ক্রিনে notification Gmail দেখানো হয় না। তবে static code ও network request-এ FormSubmit endpoint-এর Gmail address থাকে; source code দেখলে পাওয়া যায়। Address-টি গোপন বলে দাবি করা হচ্ছে না।

Email-এ নাম, ফোন, ঠিকানা, মুরগির সংখ্যা, rate, estimated weight/total, Saturday date, payment method, notes ও reference যাবে। FormSubmit তথ্য গ্রহণ করলে success দেখায়; এটি inbox delivery বা final order confirmation-এর নিশ্চয়তা নয়। চূড়ান্ত দাম ও delivery ফোনে নিশ্চিত হবে।

Order database/retry queue নেই। Email delivery FormSubmit ও mail provider-এর ওপর নির্ভর করে। ব্যর্থ হলে আবার চেষ্টা করা যাবে এবং phone/WhatsApp বিকল্প আছে।

https://formsubmit.co/
