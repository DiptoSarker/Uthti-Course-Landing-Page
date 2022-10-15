<script>
	let expanded = false;
	let expanded2 = false;
	let expanded3 = false;
	let expanded4 = false;
	// @ts-ignore
	const focusFirstDropdownLink = ({ target }) => {
		target.firstElementChild.focus();
	};

	// // let sections = document.querySelectorAll('section');
	// let windowHeight = window.innerHeight;
	// console.log(windowHeight);

	// // window.addEventListener('scroll', function () {
	// // 	const scrollTop = window.scrollY;
	// // 	sections.forEach(function (section, i) {
	// // 		if (
	// // 			section.offsetTop < scrollTop + windowHeight / 2 &&
	// // 			scrollTop < section.offsetTop + windowHeight / 2
	// // 		) {
	// // 			console.log(i);
	// // 		}
	// // 	});
	// // });
</script>

<main>
	<div class="Hackules-navbar">
		<div class="nav">
			<ul>
				<li class="selected hover:underline"><a href="#description">Instructor</a></li>
				<li class="hover:underline"><a href="#instructor">Description</a></li>
				<li class="hover:underline"><a href="#bullet">Bullet</a></li>
				<li class="hover:underline"><a href="#syllabus">Syllabus</a></li>
				<li class="hover:underline"><a href="#payment">Payment</a></li>
				<li class="hover:underline"><a href="#certificate">Certificate</a></li>
			</ul>
		</div>
	</div>
	<div class="body">
		<!-- ---------------------Left Side Start------------------- -->
		<div class="left-side">
			<div class="leftSideItems ">
				<section>
					<div id="description" class="hackules-title">
						<h1 class="desc text-5xl font-black">English For Kids</h1>
					</div>

					<div id="instructor" class="hackules-title">
						<h1 class="text-2xl font-black">Instructor</h1>
					</div>

					<div class="descc flex">
						<img class="mr-5 my-1.5 rounded-sm" src="ms.webp" alt="" height="60px" width="65px" />

						<div class="mt-2">
							<p class="mb-2 text-xl font-black">Munzareen Sahid</p>
							<p class="text-sm">
								MS (English), University of Oxford (UK); BA, MA (English), University of Dhaka;
								IELTS: 8.5
							</p>
						</div>
					</div>
				</section>

				<section>
					<div id="instructor" class="hackules-title">
						<h1 class="text-2xl font-black">Description</h1>
					</div>

					<div class="hackules-description">
						<p>
							Lorem, ipsum dolor sit amet consectetur adipisicing elit. Et a vel similique quae,
							minus ex voluptatibus ullam sapiente laborum rem non officia totam quis est obcaecati
							consequuntur temporibus molestiae odio. Pariatur minima nostrum sequi animi numquam
							facere, tempora molestias nihil vero eos assumenda, veritatis libero dolorum fugiat
							possimus beatae quas quidem quis quia, eligendi vel explicabo. Voluptatem, molestias
							molestiae, incidunt officia sequi natus quibusdam, dolor minima reprehenderit aliquam
							debitis explicabo perferendis sint accusantium aperiam culpa odit libero laboriosam.
							Blanditiis, maxime magni modi natus sequi, neque explicabo fugiat, obcaecati quasi
							dolores ratione? Quam sit enim similique laudantium quaerat mollitia ab tempore,
							accusamus cupiditate nemo voluptatem ullam, impedit quos. Atque sapiente, veritatis a
							cumque molestiae, inventore, alias laudantium expedita aperiam iste rem. Laudantium
							ipsam adipisci velit ipsa aperiam pariatur, autem dolores ad illum quibusdam,
							molestias sequi rem aut unde laboriosam tempora nisi provident sed optio cupiditate
							eligendi. Quo sint veritatis saepe mollitia ipsa voluptatem delectus officia expedita
							maxime libero.
						</p>
					</div>

					<div id="bullet" class="hackules-title">
						<h1 class="text-2xl font-black">Bullet</h1>
					</div>

					<div class="descc ">
						<div class="flex  mb-8">
							<img
								class="rounded-full mr-5 my-1.5"
								src="10mnt.jpeg"
								alt=""
								height="15px"
								width="65px"
							/>

							<div>
								<p class="ttl font-400">প্রোগ্রামটি কাদের জন্য?</p>
								<p class="text-sm mt-3">
									যারা দেশী-বিদেশী সফটওয়্যার কোম্পানি ও আইটি ফার্মগুলোতে কিংবা কোনো কোম্পানির
									প্রোডাক্ট ডেভেলপমেন্ট টিমে কাজ করতে চান। অথবা, বিভিন্ন অনলাইন ফ্রিল্যান্সিং
									মার্কেটপ্লেসে কিংবা ইন্ডিপেন্ডেন্ট টেকনিক্যাল কনসালট্যান্ট হিসেবে কাজ করতে চান।
								</p>
							</div>
						</div>

						<div class="flex mb-8">
							<img
								class="rounded-full mr-5 my-1.5"
								src="10mnt.jpeg"
								alt=""
								height="65px"
								width="65px"
							/>

							<div>
								<p class="ttl font-black">সম্পূর্ণ বিগিনাররাও পারবে?</p>
								<p class="text-sm mt-3">
									সম্পূর্ণ বিগিনাররাও এই প্রোগ্রামে যুক্ত হয়ে অ্যান্ড্রয়েড অ্যাপ ডেভেলপমেন্ট শিখতে
									পারবেন। আপনি যদি কম্পিউটার বিজ্ঞান ব্যাকগ্রাউন্ডের নাও হোন, তবুও এই প্রোগ্রামে অংশ
									নিতে পারবেন!
								</p>
							</div>
						</div>

						<div class="flex">
							<img
								class="rounded-full mr-5 my-1.5"
								src="10mnt.jpeg"
								alt=""
								height="65px"
								width="65px"
							/>

							<div>
								<p class="ttl font-black">আর কী কী লাগবে?</p>
								<p class="text-sm mt-3">
									কোর্সে Kotlin প্রোগ্রামিং ল্যাঙ্গুয়েজের উপর বেসিক থেকে অ্যাডভান্সড লেভেলের ট্রেনিং
									দেয়া হবে। পাশাপাশি অ্যান্ড্রয়েড অ্যাপ ডেভেলপমেন্টের প্রতিটি ধাপ শিখতে পারবেন। তাই
									প্রোগ্রামটির জন্য প্রোগ্রামিং নিয়ে খুব বেশি জানার প্রয়োজন নেই।
								</p>
							</div>
						</div>
					</div>

					<div id="syllabus" class="hackules-title">
						<h1 class="text-2xl font-black">Syllabus</h1>
					</div>

					<div class="syllabus">
						<div class="syl one">
							<div
								aria-expanded={expanded}
								aria-haspopup="true"
								aria-label="Nav toggle"
								on:click={() => (expanded = !expanded)}
								class=" name1 flex justify-between m-4"
							>
								<h1>English 1st paper</h1>
								<img src="down.svg" alt="" width="20px" height="20px" />
							</div>
							<div class="contents" class:expanded on:transitionend={focusFirstDropdownLink}>
								<ul>
									<div class="flex m-4 pt-5 border-t-4">
										<img class="mr-3" src="pic.svg" alt="" height="30px" width="30px" />
										<li class="">Lorem ipsum dolor sit</li>
									</div>

									<div class="flex m-4 pt-5 ">
										<img class="mr-3" src="pic.svg" alt="" height="30px" width="30px" />
										<li class="">Lorem ipsum dolor sit</li>
									</div>
									<div class="flex m-4 pt-5 ">
										<img class="mr-3" src="pic.svg" alt="" height="30px" width="30px" />
										<li class="">Lorem ipsum dolor sit</li>
									</div>
									<div class="flex m-4 pt-5 ">
										<img class="mr-3" src="pic.svg" alt="" height="30px" width="30px" />
										<li class="">Lorem ipsum dolor sit</li>
									</div>
								</ul>
							</div>
						</div>
						<div class="syl two">
							<div
								aria-expanded={expanded2}
								aria-haspopup="true"
								aria-label="Nav toggle"
								on:click={() => (expanded2 = !expanded2)}
								class=" name1 flex justify-between m-4"
							>
								<h1>Bangla 2nd paper</h1>
								<img src="down.svg" alt="" width="20px" height="20px" />
							</div>
							<div class="contents" class:expanded2 on:transitionend={focusFirstDropdownLink}>
								<ul>
									<div class="flex m-4 pt-5 border-t-4">
										<img class="mr-3" src="pic.svg" alt="" height="30px" width="30px" />
										<li class="">Lorem ipsum dolor sit</li>
									</div>
									<div class="flex m-4 pt-5 ">
										<img class="mr-3" src="pic.svg" alt="" height="30px" width="30px" />
										<li class="">Lorem ipsum dolor sit</li>
									</div>
									<div class="flex m-4 pt-5 ">
										<img class="mr-3" src="pic.svg" alt="" height="30px" width="30px" />
										<li class="">Lorem ipsum dolor sit</li>
									</div>
									<div class="flex m-4 pt-5 ">
										<img class="mr-3" src="pic.svg" alt="" height="30px" width="30px" />
										<li class="">Lorem ipsum dolor sit</li>
									</div>
								</ul>
							</div>
						</div>
						<div class="syl three">
							<div
								aria-expanded={expanded3}
								aria-haspopup="true"
								aria-label="Nav toggle"
								on:click={() => (expanded3 = !expanded3)}
								class=" name1 flex justify-between m-4"
							>
								<h1>English 2nd paper</h1>
								<img src="down.svg" alt="" width="20px" height="20px" />
							</div>
							<div class="contents" class:expanded3 on:transitionend={focusFirstDropdownLink}>
								<ul>
									<div class="flex m-4 pt-5 border-t-4">
										<img class="mr-3" src="pic.svg" alt="" height="30px" width="30px" />
										<li class="">Lorem ipsum dolor sit</li>
									</div>
									<div class="flex m-4 pt-5 ">
										<img class="mr-3" src="pic.svg" alt="" height="30px" width="30px" />
										<li class="">Lorem ipsum dolor sit</li>
									</div>
									<div class="flex m-4 pt-5 ">
										<img class="mr-3" src="pic.svg" alt="" height="30px" width="30px" />
										<li class="">Lorem ipsum dolor sit</li>
									</div>
									<div class="flex m-4 pt-5 ">
										<img class="mr-3" src="pic.svg" alt="" height="30px" width="30px" />
										<li class="">Lorem ipsum dolor sit</li>
									</div>
								</ul>
							</div>
						</div>
						<div class="syl four">
							<div
								aria-expanded={expanded4}
								aria-haspopup="true"
								aria-label="Nav toggle"
								on:click={() => (expanded4 = !expanded4)}
								class=" name1 flex justify-between m-4"
							>
								<h1>Bangla 1st paper</h1>
								<img src="down.svg" alt="" width="20px" height="20px" />
							</div>
							<div class="contents" class:expanded4 on:transitionend={focusFirstDropdownLink}>
								<ul>
									<div class="flex m-4 pt-5 border-t-4">
										<img class="mr-3" src="pic.svg" alt="" height="30px" width="30px" />
										<li class="">Lorem ipsum dolor sit</li>
									</div>
									<div class="flex m-4 pt-5 ">
										<img class="mr-3" src="pic.svg" alt="" height="30px" width="30px" />
										<li class="">Lorem ipsum dolor sit</li>
									</div>
									<div class="flex m-4 pt-5 ">
										<img class="mr-3" src="pic.svg" alt="" height="30px" width="30px" />
										<li class="">Lorem ipsum dolor sit</li>
									</div>
									<div class="flex m-4 pt-5 ">
										<img class="mr-3" src="pic.svg" alt="" height="30px" width="30px" />
										<li class="">Lorem ipsum dolor sit</li>
									</div>
								</ul>
							</div>
						</div>
					</div>
				</section>

				<section>
					<div id="certificate" class="hackules-title">
						<h1 class="text-2xl font-black">Certificate</h1>
					</div>

					<div class="hackules-description">
						<p>
							Lorem, ipsum dolor sit amet consectetur adipisicing elit. Et a vel similique quae,
							minus ex voluptatibus ullam sapiente laborum rem non officia totam quis est obcaecati
							consequuntur temporibus molestiae odio. Pariatur minima nostrum sequi animi numquam
							facere, tempora molestias nihil vero eos assumenda, veritatis libero dolorum fugiat
							possimus beatae quas quidem quis quia, eligendi vel explicabo. Voluptatem, molestias
							molestiae, incidunt officia sequi natus quibusdam, dolor minima reprehenderit aliquam
							debitis explicabo perferendis sint accusantium aperiam culpa odit libero laboriosam.
							Blanditiis, maxime magni modi natus sequi, neque explicabo fugiat, obcaecati quasi
							dolores ratione? Quam sit enim similique laudantium quaerat mollitia ab tempore,
							accusamus cupiditate nemo voluptatem ullam, impedit quos. Atque sapiente, veritatis a
							cumque molestiae, inventore, alias laudantium expedita aperiam iste rem. Laudantium
							ipsam adipisci velit ipsa aperiam pariatur, autem dolores ad illum quibusdam,
							molestias sequi rem aut unde laboriosam tempora nisi provident sed optio cupiditate
							eligendi. Quo sint veritatis saepe mollitia ipsa voluptatem delectus officia expedita
							maxime libero.
						</p>
					</div>
				</section>

				<section>
					<div id="payment" class="hackules-title">
						<h1 class="text-2xl font-black">Payment</h1>
					</div>

					<div class="hackules-description">
						<p><a class="underline" href="/#">Watch this video</a> for details on how to pay</p>
					</div>
				</section>
			</div>
		</div>

		<!-- ---------------------Right Side Start------------------- -->
		<div class="right-side">
			<div class="img sticky overflow-hidden">
				<img class="overflow-hidden" src="cover.jpeg" alt="" width="460px" height="525px" />
				<div class="text-xl mx-3.5 mt-3 flex  justify-between">
					<h1 class="text-[#7a7a7a]">প্রোমো কোড অ্যাপ্লাইড</h1>
					<h1>৳ ১৯৫০</h1>
				</div>

				<div class="mt-3 btn-class"><button class="hackules-btn">কোর্সটি কিনুন</button></div>

				<div class="flex px-6 pb-5 mt-10  justify-between border-b-2">
					<div>
						<h1 class="text-[#7a7a7a]">কোর্সটি করেছেন</h1>
						<h1>১৭৮৩৪ জন</h1>
					</div>
					<div>
						<h1 class="text-[#7a7a7a]">সময় লাগবে</h1>
						<h1>২০ ঘণ্টা</h1>
					</div>
				</div>
				<div class="flex mx-6 mt-5 mb-7 justify-between border-b-1">
					<div>
						<h1>৫টি ফ্রী ভিডিও</h1>
						<h1>৩৫ সেট কুইজ</h1>
						<h1>৩৫টি ফ্ল্যাশকার্ড</h1>
					</div>
					<div>
						<h1>৩৫টি ভিডিও</h1>
						<h1>৩৫টি নোট</h1>
					</div>
				</div>
			</div>
		</div>
	</div>
</main>

<style>
	.Hackules-navbar {
		position: fixed;
		top: 60px;
		width: 100%;
		height: 40px;
		background-color: rgb(79, 79, 79);
	}

	.nav {
		margin-left: 5.4%;
	}

	.nav ul li a {
		text-decoration: none;
		color: white;
	}

	.nav ul li {
		display: inline-block;
		padding: 10px 20px;
	}

	.nav ul li::hover {
		text-decoration: underline;
	}

	.nav ul {
		display: flex;
		justify-content: start;
	}

	.body {
		margin-top: 100px;
		width: 100%;

		background-color: antiquewhite;
		display: grid;
		grid-template-columns: 1.3fr 1fr;
	}
	.left-side {
		background-color: rgb(255, 255, 255);
		height: 100%;
	}
	.right-side {
		background-color: rgb(255, 255, 255);
		right: 0;
	}

	.leftSideItems {
		margin-left: 12%;
		margin-top: 5%;
		margin-right: 2%;
		padding: 0px 0px 20px 0px;
	}

	.hackules-title {
		padding: 0px 0px 20px 0px;
		margin-top: 30px;
	}

	.hackules-description {
		border: 1px solid rgb(218, 218, 218);
		border-radius: 5px;
		padding: 20px 20px;
	}

	.img {
		border: 1px solid rgb(218, 218, 218);
		border-radius: 5px;
	}

	.descc {
		border: 1px solid rgb(218, 218, 218);
		border-radius: 5px;
		padding: 20px 20px;
	}
	.hackules-description p {
		font-size: 1rem;
	}
	.img {
		box-sizing: border-box;
		/* position: sticky; */
		top: 12.7%;
		margin-left: 7%;
		margin-top: 10%;
		display: inline-block;
		opacity: 1;
		overflow: hidden;
	}
	.hackules-btn {
		background-color: #1daa55;
		color: white;
		font-weight: 500;
		height: 50px;
		width: 430px;
		cursor: pointer;
		border: none;
		box-shadow: 0px 0px 4px 0px rgb(181, 181, 181);
		border-radius: 5px;
	}
	.btn-class {
		margin-left: 3%;
	}
	.syl {
		box-shadow: 0px 0px 4px 0px rgb(181, 181, 181);
		border-radius: 5px;
		padding: 10px 0px;
		margin-bottom: 20px;
		cursor: pointer;
	}
	.name1 {
		transition: display 0.9s;
	}

	.contents {
		display: none;

		transition: height 0.9s;
	}

	.expanded {
		display: block;

		opacity: 1;
	}

	.expanded2 {
		display: block;
		opacity: 1;
	}

	.expanded3 {
		display: block;
		opacity: 1;
	}

	.expanded4 {
		display: block;
		opacity: 1;
	}

	.selected {
		text-decoration: underline;
	}
	.desc {
		font-weight: 1200;
	}
	.ttl {
		font-size: 1.8rem;
		font-weight: 500;
	}
</style>
