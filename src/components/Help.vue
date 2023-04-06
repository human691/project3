<template>
  <div class="scroll">
    <div class="container">
      <div class="scroll__wrap">
        <div>
          <p class="see">See how Violet can help your care delivery team.</p>
        </div>
        <div class="wrapper__btns">
          <button class="wrapper__btn">
            <img src="../assets/img/leftarrow.svg" />
          </button>
          <button class="wrapper__btn">
            <img src="../assets/img/rightarrow.svg" />
          </button>
        </div>
      </div>
      <div class="card">
        <div class="card__wrap">
          <swiper
            ref="{swiperRef}"
            :slidesPerView="3"
            :centeredSlides="true"
            :spaceBetween="30"
            :pagination="{
              type: 'fraction',
            }"
            :navigation="true"
            :modules="modules"
            class="mySwiper"
          >
            <swiper-slide
              ><div class="card1">
                <div class="card__one">
                  <div class="card__text">
                    <p class="ceo">
                      I’m the CEO of a health care organization.
                    </p>
                    <p class="my">
                      I want my patients to know my org is committed to
                      delivering inclusive care.
                    </p>
                    <div class="draw">
                      <img src="../assets/img/Group11.png" />
                    </div>
                  </div>
                </div>
              </div>
            </swiper-slide>
            <swiper-slide
              ><div class="card2">
                <div class="card__two">
                  <div class="card__text">
                    <p class="de">I’m a DEI strategy leader.</p>
                    <p class="to">
                      I want to ensure my provider team is getting the best
                      inclusivity training.
                    </p>
                    <div class="right">
                      <img src="../assets/img/rightarrow.svg" />
                    </div>
                  </div>
                </div>
              </div>
            </swiper-slide>
            <swiper-slide
              ><div class="card3">
                <div class="card__three">
                  <div class="card__text">
                    <p class="dir3">I'm a provider engagement director.</p>
                    <p class="and3">
                      I want to engage and retain my providers with more
                      benefits.
                    </p>
                    <div class="right">
                      <img src="../assets/img/rightarrow.svg" />
                    </div>
                  </div>
                </div>
              </div>
            </swiper-slide>
            <swiper-slide>
              <div class="card4">
                <div class="card__four">
                  <div class="card__text">
                    <p class="lead">I'm a health equity leader.</p>
                    <p class="with">
                      I want to close health disparity gaps by starting with my
                      own org.
                    </p>
                  </div>
                </div>
              </div>
            </swiper-slide>
            <swiper-slide
              ><div class="card5">
                <div class="card__five">
                  <div class="card__text">
                    <p class="dir5">I'm a business development manager.</p>
                    <p class="and5">
                      I want to showcase the value of our care delivery for
                      payor and employer RFPs.
                    </p>
                    <div class="right">
                      <img src="../assets/img/rightarrow.svg" />
                    </div>
                  </div>
                </div>
              </div>
            </swiper-slide>
            <swiper-slide>
              <div class="card6">
                <div class="card__six">
                  <div class="card__text">
                    <p class="dir6">I’m a clinical operations manager.</p>
                    <p class="and6">
                      I want to know what languages my providers can deliver
                      care in.
                    </p>
                    <div class="right">
                      <img src="../assets/img/rightarrow.svg" />
                    </div>
                  </div>
                </div>
              </div>
            </swiper-slide>
            <swiper-slide
              ><div class="card1">
                <div class="card__one">
                  <div class="card__text">
                    <p class="ceo">
                      I’m the CEO of a health care organization.
                    </p>
                    <p class="my">
                      I want my patients to know my org is committed to
                      delivering inclusive care.
                    </p>
                    <div class="draw">
                      <img src="../assets/img/Group11.png" />
                    </div>
                  </div>
                </div>
              </div>
            </swiper-slide>
            <swiper-slide
              ><div class="card2">
                <div class="card__two">
                  <div class="card__text">
                    <p class="de">I’m a DEI strategy leader.</p>
                    <p class="to">
                      I want to ensure my provider team is getting the best
                      inclusivity training.
                    </p>
                    <div class="right">
                      <img src="../assets/img/rightarrow.svg" />
                    </div>
                  </div>
                </div>
              </div>
            </swiper-slide>
            <swiper-slide
              ><div class="card3">
                <div class="card__three">
                  <div class="card__text">
                    <p class="dir3">I'm a provider engagement director.</p>
                    <p class="and3">
                      I want to engage and retain my providers with more
                      benefits.
                    </p>
                    <div class="right">
                      <img src="../assets/img/rightarrow.svg" />
                    </div>
                  </div>
                </div>
              </div>
            </swiper-slide>
            <swiper-slide>
              <div class="card4">
                <div class="card__four">
                  <div class="card__text">
                    <p class="lead">I'm a health equity leader.</p>
                    <p class="with">
                      I want to close health disparity gaps by starting with my
                      own org.
                    </p>
                  </div>
                </div>
              </div>
            </swiper-slide>
            <swiper-slide
              ><div class="card5">
                <div class="card__five">
                  <div class="card__text">
                    <p class="dir5">I'm a business development manager.</p>
                    <p class="and5">
                      I want to showcase the value of our care delivery for
                      payor and employer RFPs.
                    </p>
                    <div class="right">
                      <img src="../assets/img/rightarrow.svg" />
                    </div>
                  </div>
                </div>
              </div>
            </swiper-slide>
            <swiper-slide>
              <div class="card6">
                <div class="card__six">
                  <div class="card__text">
                    <p class="dir6">I’m a clinical operations manager.</p>
                    <p class="and6">
                      I want to know what languages my providers can deliver
                      care in.
                    </p>
                    <div class="right">
                      <img src="../assets/img/rightarrow.svg" />
                    </div>
                  </div>
                </div>
              </div>
            </swiper-slide>
            <swiper-slide
              ><div class="card1">
                <div class="card__one">
                  <div class="card__text">
                    <p class="ceo">
                      I’m the CEO of a health care organization.
                    </p>
                    <p class="my">
                      I want my patients to know my org is committed to
                      delivering inclusive care.
                    </p>
                    <div class="draw">
                      <img src="../assets/img/Group11.png" />
                    </div>
                  </div>
                </div>
              </div>
            </swiper-slide>
            <swiper-slide
              ><div class="card2">
                <div class="card__two">
                  <div class="card__text">
                    <p class="de">I’m a DEI strategy leader.</p>
                    <p class="to">
                      I want to ensure my provider team is getting the best
                      inclusivity training.
                    </p>
                    <div class="right">
                      <img src="../assets/img/rightarrow.svg" />
                    </div>
                  </div>
                </div>
              </div>
            </swiper-slide>
            <swiper-slide
              ><div class="card3">
                <div class="card__three">
                  <div class="card__text">
                    <p class="dir3">I'm a provider engagement director.</p>
                    <p class="and3">
                      I want to engage and retain my providers with more
                      benefits.
                    </p>
                    <div class="right">
                      <img src="../assets/img/rightarrow.svg" />
                    </div>
                  </div>
                </div>
              </div>
            </swiper-slide>
            <swiper-slide>
              <div class="card4">
                <div class="card__four">
                  <div class="card__text">
                    <p class="lead">I'm a health equity leader.</p>
                    <p class="with">
                      I want to close health disparity gaps by starting with my
                      own org.
                    </p>
                  </div>
                </div>
              </div>
            </swiper-slide>
            <swiper-slide
              ><div class="card5">
                <div class="card__five">
                  <div class="card__text">
                    <p class="dir5">I'm a business development manager.</p>
                    <p class="and5">
                      I want to showcase the value of our care delivery for
                      payor and employer RFPs.
                    </p>
                    <div class="right">
                      <img src="../assets/img/rightarrow.svg" />
                    </div>
                  </div>
                </div>
              </div>
            </swiper-slide>
            <swiper-slide>
              <div class="card6">
                <div class="card__six">
                  <div class="card__text">
                    <p class="dir6">I’m a clinical operations manager.</p>
                    <p class="and6">
                      I want to know what languages my providers can deliver
                      care in.
                    </p>
                    <div class="right">
                      <img src="../assets/img/rightarrow.svg" />
                    </div>
                  </div>
                </div>
              </div>
            </swiper-slide>
          </swiper>
        </div>
      </div>
    </div>
  </div>
  <p class="append-buttons"></p>
</template>

<script>

import { Swiper, SwiperSlide } from "swiper/vue";


import "swiper/css";

import "swiper/css/pagination";
import "swiper/css/navigation";



import { Pagination, Navigation } from "swiper";
export default {
  components: {
    Swiper,
    SwiperSlide,
  },
  setup() {
    return {
      modules: [Pagination, Navigation],
    };
  },
};
</script>



