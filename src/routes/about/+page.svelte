<script>
	import { fade } from 'svelte/transition';
	let visible = true;
</script>

<h1 class="h4">Расписание занятий</h1>

<div class="blok">
	<label>
		<input type="checkbox" class="custom-checkbox" bind:checked={visible}/>
		Расписание на июль 2023 г
	</label>
	{#if visible}
	<div  transition:fade>
			<table>
				<tr class="type">
					<td colspan="5">Расписание занятий с курсантами старшей группы ВПК Братишка на июль 2023 г</td>
				</tr>
				<tr>
					<td>Число</td>
					<td>День</td>
					<td>Часы</td>
					<td>Занятие</td>
					<td>Место проведения</td>
				</tr>
				<tr>
					<td>3</td>
					<td>пн.</td>
					<td>07.30-08.30</td>
					<td>ФИЗО</td>
					<td>стадион "Волга"</td>
				</tr>
				<tr>
					<td>4</td>
					<td>вт.</td>
					<td>18.00-20.00</td>
					<td>ТСП. Лазертаг</td>
					<td>стадион "Волга"</td>
				</tr>
				<tr>
					<td>5</td>
					<td>ср.</td>
					<td>07.30-08.30</td>
					<td>ФИЗО</td>
					<td>стадион "Волга"</td>
				</tr>
				<tr>
					<td>6</td>
					<td>чт.</td>
					<td>18.00-20.00</td>
					<td>Огневая. Страйкбол</td>
					<td>стадион "Волга"</td>
				</tr>
				<tr>
					<td>7</td>
					<td>пт.</td>
					<td>07.30-08.30</td>
					<td>ФИЗО</td>
					<td>стадион "Волга"</td>
				</tr>
				<tr>
					<td>8</td>
					<td>сб.</td>
					<td>&#8212;</td>
					<td>&#8212;</td>
					<td>&#8212;</td>
				</tr>
				<tr>
					<td>9</td>
					<td>вс.</td>
					<td>&#8212;</td>
					<td>&#8212;</td>
					<td>&#8212;</td>
				</tr>
				<tr>
					<td>10</td>
					<td>пн.</td>
					<td>07.30-08.30</td>
					<td>ФИЗО</td>
					<td>стадион "Волга"</td>
				</tr>
				<tr>
					<td>11</td>
					<td>вт.</td>
					<td>18.00-20.00</td>
					<td>ТСП. Лазертаг</td>
					<td>стадион "Волга"</td>
				</tr>
				<tr>
					<td>12</td>
					<td>ср.</td>
					<td>07.30-08.30</td>
					<td>ФИЗО</td>
					<td>стадион "Волга"</td>
				</tr>
				<tr>
					<td>13</td>
					<td>чт.</td>
					<td>18.00-20.00</td>
					<td>Огневая. Страйкбол</td>
					<td>стадион "Волга"</td>
				</tr>
				<tr>
					<td>14</td>
					<td>пт.</td>
					<td>07.30-08.30</td>
					<td>ФИЗО</td>
					<td>стадион "Волга"</td>
				</tr>
				<tr>
					<td>15</td>
					<td>сб.</td>
					<td>&#8212;</td>
					<td>&#8212;</td>
					<td>&#8212;</td>
				</tr>
				<tr>
					<td>16</td>
					<td>вс.</td>
					<td>&#8212;</td>
					<td>&#8212;</td>
					<td>&#8212;</td>
				</tr>
				<tr>
					<td>17</td>
					<td>пн.</td>
					<td>07.30-08.30</td>
					<td>ФИЗО</td>
					<td>стадион "Волга"</td>
				</tr>
				<tr>
					<td>18</td>
					<td>вт.</td>
					<td>18.00-20.00</td>
					<td>ТСП. Лазертаг</td>
					<td>стадион "Волга"</td>
				</tr>
				<tr>
					<td>19</td>
					<td>ср.</td>
					<td>07.30-08.30</td>
					<td>ФИЗО</td>
					<td>стадион "Волга"</td>
				</tr>
				<tr>
					<td>20</td>
					<td>чт.</td>
					<td>18.00-20.00</td>
					<td>Огневая. Страйкбол</td>
					<td>стадион "Волга"</td>
				</tr>
				<tr>
					<td>21</td>
					<td>пт.</td>
					<td>07.30-08.30</td>
					<td>ФИЗО</td>
					<td>стадион "Волга"</td>
				</tr>
				<tr>
					<td>22</td>
					<td>сб.</td>
					<td>&#8212;</td>
					<td>&#8212;</td>
					<td>&#8212;</td>
				</tr>
				<tr>
					<td>23</td>
					<td>вс.</td>
					<td>&#8212;</td>
					<td>&#8212;</td>
					<td>&#8212;</td>
				</tr>
				<tr>
					<td>24</td>
					<td>пн.</td>
					<td>07.30-08.30</td>
					<td>ФИЗО</td>
					<td>стадион "Волга"</td>
				</tr>
				<tr>
					<td>25</td>
					<td>вт.</td>
					<td>18.00-20.00</td>
					<td>ТСП. Лазертаг</td>
					<td>стадион "Волга"</td>
				</tr>
				<tr>
					<td>26</td>
					<td>ср.</td>
					<td>07.30-08.30</td>
					<td>ФИЗО</td>
					<td>стадион "Волга"</td>
				</tr>
				<tr>
					<td>27</td>
					<td>чт.</td>
					<td>18.00-20.00</td>
					<td>Огневая. Страйкбол</td>
					<td>стадион "Волга"</td>
				</tr>
				<tr>
					<td>28</td>
					<td>пт.</td>
					<td>07.30-08.30</td>
					<td>ФИЗО</td>
					<td>стадион "Волга"</td>
				</tr>
				<tr>
					<td>29</td>
					<td>сб.</td>
					<td>&#8212;</td>
					<td>&#8212;</td>
					<td>&#8212;</td>
				</tr>
				<tr>
					<td>30</td>
					<td>вс.</td>
					<td>&#8212;</td>
					<td>&#8212;</td>
					<td>&#8212;</td>
				</tr>
				<tr>
					<td>31</td>
					<td>пн.</td>
					<td>&#8212;</td>
					<td>&#8212;</td>
					<td>&#8212;</td>
				</tr>
			</table>
		</div>
	{/if}
</div>

<footer class="new_footer_area bg_color">
	<div class="new_footer_top">
		<div class="container">
			<div class="row">
				<div class="col-lg-3 col-md-6">
					<div class="f_widget company_widget wow fadeInLeft" data-wow-delay="0.2s" style="visibility: visible; animation-delay: 0.2s; animation-name: fadeInLeft;">
						<h3 id="hh3" class="f-title f_600 t_color f_size_18">Связаться</h3>
						<p>Не пропустите ни одной новой новости в нашей организации!</p>
						<form action="#" class="f_subscribe_two mailchimp" method="post" novalidate="true" _lpchecked="1">
							<p class="mchimp-errmessage" style="display: none;"></p>
							<p class="mchimp-sucmessage" style="display: none;"></p>
						</form>
					</div>
				</div>
				<div class="col-lg-3 col-md-6">
					<div class="f_widget about-widget pl_70 wow fadeInLeft" data-wow-delay="0.6s" style="visibility: visible; animation-delay: 0.6s; animation-name: fadeInLeft;">
						<h3 id="hh1" class="f-title f_600 t_color f_size_18">Помощь</h3>
						<ul class="list-unstyled f_list">
							<li><a href="#">FAQ</a></li>
							<li><a href="#">Term &amp; conditions</a></li>
							<li><a href="#">Документация</a></li>
							<li><a href="#">Политика поддержки</a></li>
						</ul>
					</div>
				</div>
				<div class="col-lg-3 col-md-6">
					<div class="f_widget social-widget pl_70 wow fadeInLeft" data-wow-delay="0.8s" style="visibility: visible; animation-delay: 0.8s; animation-name: fadeInLeft;">
						<h3 id="hh1" class="f-title f_600 t_color f_size_18">Каналы</h3>
						<div class="f_social_icon">
							<a href="https://www.youtube.com/@a_nevsky30" class="fab_youtube"><img src="youtube_br.png"></a>
							<a href="https://vk.com/bratishka_ahtubinsk" class="fab fa-twitter"><img src="vkontakte.png"></a>
							<a href="#" class="fab fa-linkedin"></a>
							<a href="#" class="fab fa-pinterest"></a>
						</div>
					</div>
				</div>
			</div>
		</div>
		<div class="footer_bg">
			<div class="footer_bg_one"></div>
			<div class="footer_bg_two"></div>
		</div>
	</div>
	<div class="footer_bottom">
		<div class="container"></div>
	</div>
</footer>