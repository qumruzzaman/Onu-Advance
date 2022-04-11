<div id="readme" class="Box-body readme blob js-code-block-container p-5 p-xl-6 gist-border-0">
    <article class="markdown-body entry-content container-lg" itemprop="text"><h1 dir="auto"><a id="user-content-গিট-কমান্ডস" class="anchor" aria-hidden="true" href="#গিট-কমান্ডস"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.775 3.275a.75.75 0 001.06 1.06l1.25-1.25a2 2 0 112.83 2.83l-2.5 2.5a2 2 0 01-2.83 0 .75.75 0 00-1.06 1.06 3.5 3.5 0 004.95 0l2.5-2.5a3.5 3.5 0 00-4.95-4.95l-1.25 1.25zm-4.69 9.64a2 2 0 010-2.83l2.5-2.5a2 2 0 012.83 0 .75.75 0 001.06-1.06 3.5 3.5 0 00-4.95 0l-2.5 2.5a3.5 3.5 0 004.95 4.95l1.25-1.25a.75.75 0 00-1.06-1.06l-1.25 1.25a2 2 0 01-2.83 0z"></path></svg></a>গিট কমান্ডস</h1>
<h2 dir="auto"><a id="user-content-অনুবাদিত-সংস্করণ" class="anchor" aria-hidden="true" href="#অনুবাদিত-সংস্করণ"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.775 3.275a.75.75 0 001.06 1.06l1.25-1.25a2 2 0 112.83 2.83l-2.5 2.5a2 2 0 01-2.83 0 .75.75 0 00-1.06 1.06 3.5 3.5 0 004.95 0l2.5-2.5a3.5 3.5 0 00-4.95-4.95l-1.25 1.25zm-4.69 9.64a2 2 0 010-2.83l2.5-2.5a2 2 0 012.83 0 .75.75 0 001.06-1.06 3.5 3.5 0 00-4.95 0l-2.5 2.5a3.5 3.5 0 004.95 4.95l1.25-1.25a.75.75 0 00-1.06-1.06l-1.25 1.25a2 2 0 01-2.83 0z"></path></svg></a>অনুবাদিত সংস্করণ</h2>
<ul dir="auto">
<li><a href="/abNomanWeb/git-commands/blob/master/READMEen.md">English version (original)</a></li>
<li><a href="/abNomanWeb/git-commands/blob/master/READMEbn.md">বাংলা সংস্করণ</a></li>
</ul>
<hr>
<p dir="auto"><em>প্রায়শই ব্যবহৃত গিট কমান্ডের তালিকা</em></p>
<p dir="auto"><em>আপনি যদি গিট এলিয়াসে আগ্রহী হন তবে এখানে '.bash_profile' এ দেখুন: <a href="https://github.com/joshnh/bash_profile/blob/master/.bash_profile">https://github.com/joshnh/bash_profile/blob/master/.bash_profile</a></em></p>
<p dir="auto"><em>অনুবাদে মূল ইংরেজি শব্দগুলো সংরক্ষণ করা হয়েছে, যেখানে "রিপোজিটরি" শব্দটিকে "রেপো", "লোকাল" কে "লোকাল" এবং "রিমোট" কে "রিমোট" হিসেবে অনুবাদ করা হয়েছে। আশা করি এগুলো বিবেচনা করলে ডকুমেন্ট থেকে উপকৃত হতে পারবেন .</em></p>
<p dir="auto">--</p>
<h3 dir="auto"><a id="user-content-প্রজেক্ট-নামানো-ও-তৈরি-করা" class="anchor" aria-hidden="true" href="#প্রজেক্ট-নামানো-ও-তৈরি-করা"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.775 3.275a.75.75 0 001.06 1.06l1.25-1.25a2 2 0 112.83 2.83l-2.5 2.5a2 2 0 01-2.83 0 .75.75 0 00-1.06 1.06 3.5 3.5 0 004.95 0l2.5-2.5a3.5 3.5 0 00-4.95-4.95l-1.25 1.25zm-4.69 9.64a2 2 0 010-2.83l2.5-2.5a2 2 0 012.83 0 .75.75 0 001.06-1.06 3.5 3.5 0 00-4.95 0l-2.5 2.5a3.5 3.5 0 004.95 4.95l1.25-1.25a.75.75 0 00-1.06-1.06l-1.25 1.25a2 2 0 01-2.83 0z"></path></svg></a>প্রজেক্ট নামানো ও তৈরি করা</h3>
<table>
<thead>
<tr>
<th>কমান্ড</th>
<th>বর্ণনা</th>
</tr>
</thead>
<tbody>
<tr>
<td><code>git init</code></td>
<td>একটি লোকাল গিট রেপো শুরু করুন</td>
</tr>
<tr>
<td><code>git clone ssh://git@github.com/[username]/[repository-name].git</code></td>
<td>একটি রিমোট রেপোর লোকাল অনুলিপি তৈরি করুন</td>
</tr>
</tbody>
</table>
<h3 dir="auto"><a id="user-content-বেসিক-স্ন্যাপশট" class="anchor" aria-hidden="true" href="#বেসিক-স্ন্যাপশট"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.775 3.275a.75.75 0 001.06 1.06l1.25-1.25a2 2 0 112.83 2.83l-2.5 2.5a2 2 0 01-2.83 0 .75.75 0 00-1.06 1.06 3.5 3.5 0 004.95 0l2.5-2.5a3.5 3.5 0 00-4.95-4.95l-1.25 1.25zm-4.69 9.64a2 2 0 010-2.83l2.5-2.5a2 2 0 012.83 0 .75.75 0 001.06-1.06 3.5 3.5 0 00-4.95 0l-2.5 2.5a3.5 3.5 0 004.95 4.95l1.25-1.25a.75.75 0 00-1.06-1.06l-1.25 1.25a2 2 0 01-2.83 0z"></path></svg></a>বেসিক স্ন্যাপশট</h3>
<table>
<thead>
<tr>
<th>কমান্ড</th>
<th>বর্ণনা</th>
</tr>
</thead>
<tbody>
<tr>
<td><code>git status</code></td>
<td>স্ট্যটাস চেক করুন</td>
</tr>
<tr>
<td><code>git add [file-name.txt]</code></td>
<td>স্টেজিং এরিয়ায় একটি ফাইল এড করুন</td>
</tr>
<tr>
<td><code>git add -A</code></td>
<td>স্টেজিং এলাকায় সমস্ত নতুন এবং পরিবর্তিত ফাইল এড করুন</td>
</tr>
<tr>
<td><code>git commit -m "[commit message]"</code></td>
<td>পরিবর্তনগুলোর কমিট (ব্যাখ্যা) করুন</td>
</tr>
<tr>
<td><code>git rm -r [file-name.txt]</code></td>
<td>ফাইল (বা ডিরেক্টরি) অপসারণ করুন</td>
</tr>
</tbody>
</table>
<h3 dir="auto"><a id="user-content-ব্রাঞ্চিং-এবং-মার্জিং" class="anchor" aria-hidden="true" href="#ব্রাঞ্চিং-এবং-মার্জিং"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.775 3.275a.75.75 0 001.06 1.06l1.25-1.25a2 2 0 112.83 2.83l-2.5 2.5a2 2 0 01-2.83 0 .75.75 0 00-1.06 1.06 3.5 3.5 0 004.95 0l2.5-2.5a3.5 3.5 0 00-4.95-4.95l-1.25 1.25zm-4.69 9.64a2 2 0 010-2.83l2.5-2.5a2 2 0 012.83 0 .75.75 0 001.06-1.06 3.5 3.5 0 00-4.95 0l-2.5 2.5a3.5 3.5 0 004.95 4.95l1.25-1.25a.75.75 0 00-1.06-1.06l-1.25 1.25a2 2 0 01-2.83 0z"></path></svg></a>ব্রাঞ্চিং এবং মার্জিং</h3>
<table>
<thead>
<tr>
<th>কমান্ড</th>
<th>বর্ণনা</th>
</tr>
</thead>
<tbody>
<tr>
<td><code>git branch</code></td>
<td>ব্রাঞ্চের তালিকা (তারকা বর্তমান ব্রাঞ্চ নির্দেশ করে)</td>
</tr>
<tr>
<td><code>git branch -a</code></td>
<td>সকল ব্রাঞ্চের তালিকা (লোকাল এবং রিমোট উভয়ই একত্রে)</td>
</tr>
<tr>
<td><code>git branch [branch name]</code></td>
<td>নতুন ব্রাঞ্চ তৈরি করুন</td>
</tr>
<tr>
<td><code>git branch -d [branch name]</code></td>
<td>ব্রাঞ্চ ডিলিট করুন</td>
</tr>
<tr>
<td><code>git push origin --delete [branch name]</code></td>
<td>রিমোট ব্রাঞ্চ ডিলিট করুন</td>
</tr>
<tr>
<td><code>git checkout -b [branch name]</code></td>
<td>একটি নতুন ব্রাঞ্চ তৈরি করুন এবং এতে স্যুইচ করুন</td>
</tr>
<tr>
<td><code>git checkout -b [branch name] origin/[branch name]</code></td>
<td>রিমোট ব্রাঞ্চ ক্লোন করুন এবং এটিতে স্যুইচ করুন</td>
</tr>
<tr>
<td><code>git branch -m [old branch name] [new branch name]</code></td>
<td>লোকাল ব্রাঞ্চের নাম পরিবর্তন করুন</td>
</tr>
<tr>
<td><code>git checkout [branch name]</code></td>
<td>স্পেসিফিক ব্রাঞ্চে স্যুইচ করুন</td>
</tr>
<tr>
<td><code>git checkout -</code></td>
<td>সর্বশেষ চেক করা ব্রাঞ্চে স্যুইচ করুন</td>
</tr>
<tr>
<td><code>git checkout -- [file-name.txt]</code></td>
<td>স্পেসিফিক ফাইলের পরিবর্তন মুছে ফেলুন</td>
</tr>
<tr>
<td><code>git merge [branch name]</code></td>
<td>একটিভ ব্রাঞ্চের সাথে আরেকটি ব্রাঞ্চ মার্জ করুন</td>
</tr>
<tr>
<td><code>git merge [source branch] [target branch]</code></td>
<td>টার্গেট ব্রাঞ্চের সাথে স্পেসিফিক ব্রাঞ্চ একত্রিত করুন</td>
</tr>
<tr>
<td><code>git stash</code></td>
<td>অসমাপ্ত কাজের ডিরেক্টরিতে পরিবর্তনগুলি সংরক্ষণ করুন</td>
</tr>
<tr>
<td><code>git stash clear</code></td>
<td>স্ট্যাশ এন্টিগুলো সরিয়ে ফেলুন</td>
</tr>
</tbody>
</table>
<h3 dir="auto"><a id="user-content-শেয়ারিং-এবং-আপডেটিং-প্রকল্পগুলি" class="anchor" aria-hidden="true" href="#শেয়ারিং-এবং-আপডেটিং-প্রকল্পগুলি"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.775 3.275a.75.75 0 001.06 1.06l1.25-1.25a2 2 0 112.83 2.83l-2.5 2.5a2 2 0 01-2.83 0 .75.75 0 00-1.06 1.06 3.5 3.5 0 004.95 0l2.5-2.5a3.5 3.5 0 00-4.95-4.95l-1.25 1.25zm-4.69 9.64a2 2 0 010-2.83l2.5-2.5a2 2 0 012.83 0 .75.75 0 001.06-1.06 3.5 3.5 0 00-4.95 0l-2.5 2.5a3.5 3.5 0 004.95 4.95l1.25-1.25a.75.75 0 00-1.06-1.06l-1.25 1.25a2 2 0 01-2.83 0z"></path></svg></a>শেয়ারিং এবং আপডেটিং প্রকল্পগুলি</h3>
<table>
<thead>
<tr>
<th>কমান্ড</th>
<th>বর্ণনা</th>
</tr>
</thead>
<tbody>
<tr>
<td><code>git push origin [branch name]</code></td>
<td>রিমোট রেপোতে ব্রাঞ্চ পুশ করুন</td>
</tr>
<tr>
<td><code>git push -u origin [branch name]</code></td>
<td>রিমোট রেপোতে পরিবর্তনগুলি পুশ করুন (এবং ব্রাঞ্চটি মনে রাখুন)</td>
</tr>
<tr>
<td><code>git push</code></td>
<td>রিমোট রিপোজিটরিতে পরিবর্তনগুলি পুশ করুন (যে শাখাটি ইতিমধ্যে মনে রাখা হয়েছে)</td>
</tr>
<tr>
<td><code>git push origin --delete [branch name]</code></td>
<td>রিমোট ব্রাঞ্চ ডিলিট করুন</td>
</tr>
<tr>
<td><code>git pull</code></td>
<td>সর্বশেষ কমিট দ্বারা স্থানীয় রেপো আপডেট করুন</td>
</tr>
<tr>
<td><code>git pull origin [branch name]</code></td>
<td>রিমোট রেপো থেকে পরিবর্তনগুলি পুল করুন</td>
</tr>
<tr>
<td><code>git remote add origin ssh://git@github.com/[username]/[repository-name].git</code></td>
<td>রিমোট রেপো এড করুন</td>
</tr>
<tr>
<td><code>git remote set-url origin ssh://git@github.com/[username]/[repository-name].git</code></td>
<td>রেপোর অরিজিন ব্রাঞ্চে SSH এ সেট করুন</td>
</tr>
</tbody>
</table>
<h3 dir="auto"><a id="user-content-পর্যালোচনা-এবং-তুলনা" class="anchor" aria-hidden="true" href="#পর্যালোচনা-এবং-তুলনা"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.775 3.275a.75.75 0 001.06 1.06l1.25-1.25a2 2 0 112.83 2.83l-2.5 2.5a2 2 0 01-2.83 0 .75.75 0 00-1.06 1.06 3.5 3.5 0 004.95 0l2.5-2.5a3.5 3.5 0 00-4.95-4.95l-1.25 1.25zm-4.69 9.64a2 2 0 010-2.83l2.5-2.5a2 2 0 012.83 0 .75.75 0 001.06-1.06 3.5 3.5 0 00-4.95 0l-2.5 2.5a3.5 3.5 0 004.95 4.95l1.25-1.25a.75.75 0 00-1.06-1.06l-1.25 1.25a2 2 0 01-2.83 0z"></path></svg></a>পর্যালোচনা এবং তুলনা</h3>
<table>
<thead>
<tr>
<th>কমান্ড</th>
<th>বর্ণনা</th>
</tr>
</thead>
<tbody>
<tr>
<td><code>git log</code></td>
<td>পরিবর্তনগুলি দেখুন</td>
</tr>
<tr>
<td><code>git log --summary</code></td>
<td>পরিবর্তন দেখুন (বিস্তারিত)</td>
</tr>
<tr>
<td><code>git log --oneline</code></td>
<td>পরিবর্তনগুলি দেখুন (সংক্ষেপে)</td>
</tr>
<tr>
<td><code>git diff [source branch] [target branch]</code></td>
<td>মার্জ করার আগে চেঞ্জগুলির প্রিভিউ দেখুন</td>
</tr>
</tbody>
</table>
</article>
  </div>

    </div>
