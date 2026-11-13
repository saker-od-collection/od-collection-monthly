OD COLLECTION MONTHLY – HOME SCREEN APP (PWA)
এটি Version 2-এর ইনস্টলযোগ্য PWA প্যাকেজ।

গুরুত্বপূর্ণ:
- Home Screen-এ আলাদা আইকনসহ অ্যাপ হিসেবে ইনস্টল করতে প্রথমবার HTTPS ওয়েব ঠিকানায় প্রকাশ করতে হবে।
- শুধু ZIP বা index.html ফোনে খুললে Service Worker চালু হবে না; ফলে প্রকৃত offline app install হবে না।
- HTTPS ঠিকানায় প্রথমবার একবার খুলে Install app / Add to Home Screen করতে হবে। এরপর একবার লোড হলে অফলাইনে ব্যবহার করা যাবে।
- PWA ইনস্টল করার আগে পুরোনো সফটওয়্যার থেকে Export Backup করে রাখুন।
- PWA-তে প্রথমবার Import Backup করে পুরোনো সদস্যদের তথ্য আনুন; ব্রাউজার localStorage আলাদা হতে পারে।
- নিয়মিত Backup Export করুন।
ফাইলসমূহ: index.html, manifest.webmanifest, service-worker.js, icons/
