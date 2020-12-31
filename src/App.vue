<template>
    <div class="crm">
        <div class="container-x">
            <div class="row">
                <div class="col-lg-4 col-md-4 col-sm-12 col-xs-12">
                    <div class="main-box sct">
                        <div class="head">
                            <div class="u-d">
                                <img
                                    src="./assets/icons/tkticon.svg"
                                    alt="icon"
                                />
                                <div class="u-info">
                                    <p class="name">ემი იტაბაიაში</p>
                                    <p class="deal-name">Deal Name Here</p>
                                </div>
                            </div>
                            <div class="list">
                                <div
                                    class="l-o"
                                    v-for="(obj, index) in [1, 2, 3]"
                                    :key="index"
                                >
                                    <span class="o-name"
                                        >Alliance Privilege - 2717</span
                                    >
                                    <span class="price">132084.00 $</span>
                                </div>
                            </div>
                        </div>
                        <div class="bottom">
                            <span class="bt">ჯამი:</span>
                            <div class="sum">
                                <span>76 438,25 $</span>
                                <img
                                    src="./assets/icons/bigedit.svg"
                                    alt="pen"
                                />
                            </div>
                        </div>
                    </div>
                </div>
                <div class="col-lg-8 col-md-8 col-sm-12 col-xs-12">
                    <div class="calc sct">
                        <div class="bars">
                            <span class="active">თარიღით გამოთვლა</span>
                            <span>გადახდებით გამოთვლა</span>
                            <span>იპოთეკა</span>
                            <span>ერთიანი გადახდა</span>
                        </div>
                        <div class="content">
                            <label for="start-date">
                                <span>დაწყების თარიღი</span>
                                <input type="text" name="start-date" />
                            </label>
                            <label for="end-date">
                                <span>დასრულების თარიღი</span>
                                <input type="text" name="end-date" />
                            </label>
                            <label for="pay-date">
                                <span>გადახდის არეალი</span>
                                <select name="pay-date">
                                    <option value="კვარტლური">კვარტლური</option>
                                    <option value="კვარტლური">კვარტლური</option>
                                    <option value="კვარტლური">კვარტლური</option>
                                </select>
                            </label>
                            <label for="first-pay">
                                <span>პირველადი შენატანი</span>
                                <input type="text" name="first-pay" />
                            </label>
                            <label for="last-pay">
                                <span>საბოლოო შენატანი</span>
                                <input type="text" name="last-pay" />
                            </label>
                            <label for="warranty-pay">
                                <span>საგარანტიო თანხა</span>
                                <input type="text" name="warranty-pay" />
                            </label>
                        </div>
                        <div class="buttons">
                            <div class="calc-btn">გამოთვლა</div>
                            <div class="clear-btn">გასუფთავება</div>
                        </div>
                    </div>
                </div>
            </div>
            <div class="row">
                <div class="col-xs-12">
                    <div class="green-bar sct">
                        <span>მიმდინარე</span>
                        <span class="deal">Deal Name</span>
                    </div>
                </div>
            </div>
            <div class="row">
                <div class="col-lg-7 col-md-7 col-sm-12 col-xs-12">
                    <div class="l-list sct">
                        <div class="head">
                            <div class="n">#</div>
                            <div class="date">თარიღი</div>
                            <div class="sum">თანხა</div>
                            <div class="nsum">ნაშთი</div>
                        </div>
                        <div class="content">
                            <div
                                class="obj"
                                v-for="(deal, index) in [
                                    1,
                                    2,
                                    3,
                                    4,
                                    5,
                                    6,
                                    7,
                                    8,
                                    9,
                                ]"
                                :key="index"
                            >
                                <span class="n">1</span>
                                <span class="date">2 იანვარი 2020</span>
                                <span class="sum">2916.00 $</span>
                                <span class="nsum">32 084.00 $</span>
                            </div>
                        </div>
                        <div class="plus">+</div>
                    </div>
                </div>
                <div class="col-lg-5 col-md-5 col-sm-12 col-xs-12">
                    <div class="deal-info sct">
                        <div class="z-list">
                            <div class="z">
                                <span class="name">გადახდის ტიპი</span>
                                <span class="v">შიდა განვადება</span>
                            </div>
                            <div class="z">
                                <span class="name">საწყისი თარიღი</span>
                                <span class="v">5 იანვარი 2020</span>
                            </div>
                            <div class="z">
                                <span class="name">დასრულების თარიღი</span>
                                <span class="v">5 იანვარი 2024</span>
                            </div>
                            <div class="z">
                                <span class="name">პირველადი შენატანი</span>
                                <span class="v">2 084.00 $</span>
                            </div>
                            <div class="z">
                                <span class="name">საბოლოო შენატანი</span>
                                <span class="v">-</span>
                            </div>
                            <div class="z">
                                <span class="name">საგარანტიო თანხა</span>
                                <span class="v">-</span>
                            </div>
                            <div class="z">
                                <span class="name"
                                    >საშუალო კვ.მ ღირებულება</span
                                >
                                <span class="v">2 084.00 $</span>
                            </div>
                            <div class="z">
                                <span class="name">სრული ფართი</span>
                                <span class="v">85.65 m2</span>
                            </div>
                            <div class="z">
                                <span class="name">გადახდების რაოდენობა</span>
                                <span class="v">15</span>
                            </div>
                            <div class="z">
                                <span class="name">ფასდაკლება</span>
                                <span class="v">2%</span>
                            </div>
                            <div class="z">
                                <span class="name">ლოალობის ქულა</span>
                                <span class="v">1500</span>
                            </div>
                        </div>
                        <div class="sum-label">
                            <img src="./assets/icons/receipt.svg" alt="rec" />
                            <span class="s">32 084.00 $</span>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    name: "App",
};
</script>

<style lang="scss">
@import "./scss/general.scss";

.crm {
    padding: 20px 0;
    .sct {
        margin-top: 8px;
        margin-bottom: 8px;
        background: #fff;
        border-radius: 8px;
        overflow: hidden;
    }
    .main-box {
        min-height: 340px;
        box-sizing: border-box;
        padding: 24px;
        display: flex;
        flex-direction: column;
        justify-content: space-between;
        .head {
            .u-d {
                display: flex;
                padding-bottom: 16px;
                border-bottom: 1px dashed var(--color-gray-light);
                margin-bottom: 16px;
                .u-info {
                    padding-left: 16px;
                    p {
                        margin: 0;
                    }
                    .name {
                        font-weight: 500;
                        color: var(--color-gray);
                        padding-bottom: 4px;
                    }
                    .deal-name {
                        color: var(--color-gray-light);
                        font-size: 14px;
                    }
                }
                img {
                    width: 40px;
                    height: 40px;
                }
            }
            .list {
                .l-o {
                    display: flex;
                    justify-content: space-between;
                    margin-bottom: 10px;
                    color: var(--color-gray);
                    .o-name {
                        font-weight: 300;
                    }
                    .price {
                        font-weight: 500;
                    }
                }
            }
        }
        .bottom {
            display: flex;
            justify-content: space-between;
            align-items: center;
            color: var(--color-gray);
            padding-top: 12px;
            border-top: 1px dashed var(--color-gray-light);
            span.bt {
                font-weight: 300;
            }
            .sum {
                display: flex;
                align-items: center;
                span {
                    margin-right: 10px;
                    font-weight: 500;
                    color: var(--color-green);
                }
                img {
                }
            }
        }
    }
    .calc {
        min-height: 340px;
        box-sizing: border-box;
        display: flex;
        flex-direction: column;
        justify-content: space-between;
        .bars {
            display: flex;
            align-items: center;
            justify-content: space-between;
            background: var(--color-silver);
            span {
                color: var(--color-gray);
                white-space: nowrap;
                padding: 0 20px;
                cursor: pointer;
                height: 50px;
                line-height: 50px;
                border-top-right-radius: 11px;
                border-top-left-radius: 11px;
                &.active {
                    background: #fff;
                }
            }
        }
        .content {
            padding: 4px 8px 0;
            display: flex;
            flex-wrap: wrap;
            justify-content: space-around;
            label {
                width: 220px;
                display: flex;
                flex-direction: column;
                margin: 12px 10px;
                span {
                    color: var(--color-gray);
                    font-weight: 300;
                    display: block;
                }
                input,
                select {
                    padding-left: 12px;
                    font-size: 16px;
                    border-radius: 6px;
                    margin-top: 8px;
                    border: 1px solid transparent;
                    height: 50px;
                    transition: 0.2s;
                    color: var(--color-gray);
                    background-color: var(--color-silver);
                    box-sizing: border-box;
                    &:hover {
                        border: 1px solid var(--color-gray);
                    }
                    &:focus {
                        outline: none;
                    }
                }
            }
        }
        .buttons {
            display: flex;
            justify-content: space-between;
            padding: 0 20px 16px;
            .calc-btn {
                cursor: pointer;
                background-color: var(--color-blue);
                color: #fff;
                width: 200px;
                height: 50px;
                line-height: 50px;
                text-align: center;
                border-radius: 8px;
                box-sizing: border-box;
            }
            .clear-btn {
                cursor: pointer;
                width: 170px;
                height: 50px;
                line-height: 50px;
                text-align: center;
                border-radius: 8px;
                box-sizing: border-box;
                border: 1px solid var(--color-gray);
            }
        }
    }
    .green-bar {
        background: var(--color-green);
        color: #fff;
        padding: 25px;
        display: flex;
        align-items: center;
        span {
        }
        .deal {
            margin-left: 20px;
            position: relative;
            &::before {
                position: absolute;
                content: "";
                height: 20px;
                width: 2px;
                border-radius: 4px;
                background: var(--color-green-light);
                left: -11px;
            }
        }
    }
    .l-list {
        padding: 0 20px;
        .head {
            padding: 0 12px;
            font-weight: 300;
            color: var(--color-blue);
            display: flex;
            justify-content: space-between;
            align-items: center;
            height: 50px;
            border-bottom: 1px dashed var(--color-gray-light);
        }
        .content {
            display: flex;
            flex-direction: column;
            .obj {
                display: flex;
                justify-content: space-between;
                align-items: center;
                height: 42px;
                border-bottom: 1px dashed var(--color-gray-light);
                span {
                    font-size: 17px;
                    color: var(--color-gray);
                    &.sum,
                    &.nsum {
                        font-weight: 500;
                    }
                }
                &:hover {
                    span {
                        color: var(--color-black);
                    }
                }
            }
        }
        .plus {
            margin: 8px auto 12px;
            height: 30px;
            width: 140px;
            text-align: center;
            line-height: 30px;
            background-color: #535c69;
            cursor: pointer;
            border-radius: 6px;
            color: #fff;
            font-size: 18px;
            &:hover {
                background-color: #737d98;
            }
        }
    }
    .deal-info {
        background-color: var(--color-blue);
        color: #fff;
        padding: 16px 24px;
        .z-list {
            .z {
                display: flex;
                justify-content: space-between;
                padding: 12px 0;
                border-bottom: 1px dashed #fff;
                &:last-child {
                    border-bottom: none;
                }
                .name {
                    font-weight: 300;
                }
                .v {
                    font-weight: 500;
                }
            }
        }
        .sum-label {
            margin-top: 12px;
            height: 68px;
            border: 1px dashed #fff;
            border-radius: 8px;
            display: flex;
            align-items: center;
            justify-content: center;
        }
    }
}
</style>