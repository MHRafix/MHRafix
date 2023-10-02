
		<div
			className='flex_layout'
			style={{
				margin: 'auto',
				width: '90%',
				height: '100vh',
			}}
		>
			<div className='myImage' data-aos='fade-up'>
				<img className='profilePic' src={"https://rafix.netlify.app/assets/me-4143a754.jpg"} alt='MyProfileImage' />
			</div>

			<Space w={60} />

			<div className='themeDetails' data-aos='fade-down'>
				<h3 className='specialitis'>Hey,</h3>
				<h1 className='nameHeading'>I'm Mehedi H. Rafiz</h1>
				<h3 className='specialitis'>Full Stack Web Developer</h3>
				<Group>
					<div style={getStyle('rgb(238 238 238 / 49%)')}>
						<SiNextdotjs size={20} color='white' /> &nbsp; NEXT JS
					</div>
					<div style={getStyle('rgb(255 239 1 / 45%)')}>
						<SiTsnode size={20} color='#ffef01' /> &nbsp; TS
					</div>
					<div style={getStyle('rgb(175 34 34 / 67%)')}>
						<SiNestjs size={20} color='red' /> &nbsp; NEST JS
					</div>
					<div style={getStyle('rgb(6 252 178 / 40%)')}>
						<SiMongodb size={20} color='#12B886' /> &nbsp; MONGO DB
					</div>
				</Group>

				<Space h={10} />

				<p className='shortDesc'>
					Trying to find a web developer,,,? Look no further, I'm your guy. I'm
					a professional Full-Stack Web Application Developer.
				</p>

				<button onClick={() => linkHandle(myResumeLink)} className='regularBtn'>
					Download Resume <HiDownload size={20} className='icon fa' />
				</button>
			</div>
		</div>
