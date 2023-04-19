<li>
                            <a href="#">shop</a>
                            <div class="shop__menu">
                                <ul class="sub__menu">
                                    <li>
                                        <ul>
                                            <li>
                                                <h5>Explore By Category</h5>
                                            </li>
                                            <li>
                                                <a href="#">necklaces & pendants</a>
                                            </li>
                                            <li>
                                                <a href="#">bracelets</a>
                                            </li>
                                            <li>
                                                <a href="#">earrings</a>
                                            </li>
                                            <li>
                                                <a href="#">rings</a>
                                            </li>
                                            <li>
                                                <a href="#">pearls</a>
                                            </li>
                                            <li>
                                                <a href="#">charms</a>
                                            </li>
                                            <li>
                                                <a href="#">brooches</a>
                                            </li>
                                            <li>
                                                <a href="#">silver jewellery</a>
                                            </li>
                                            <li>
                                                <a href="#">men's cufflinks</a>
                                            </li>
                                        </ul>
                                    </li>
                                    <li>
                                        <ul>
                                            <li>
                                                <h5>H&I Collections</h5>
                                            </li>
                                            <li>
                                                <a href="#">scottish gold</a>
                                            </li>
                                            <li>
                                                <a href="#">luna</a>
                                            </li>
                                            <li>
                                                <a href="#">signature</a>
                                            </li>
                                            <li>
                                                <a href="#">donut</a>
                                            </li>
                                            <li>
                                                <a href="#">chain link</a>
                                            </li>
                                            <li>
                                                <a href="#">dewdrop</a>
                                            </li>
                                            <li>
                                                <a href="#">duke</a>
                                            </li>
                                            <li>
                                                <a href="#">flora</a>
                                            </li>
                                        </ul>
                                    </li>
                                    <li>
                                        <ul>
                                            <li>
                                                <h5>Explore By Brand</h5>
                                            </li>
                                            <li>
                                                <a href="#">Fope</a>
                                            </li>
                                            <li>
                                                <a href="#">georg jenson</a>
                                            </li>
                                            <li>
                                                <a href="#">charlotte chesnais</a>
                                            </li>
                                        </ul>
                                    </li>
                                </ul>
                            </div>
                        </li>
                        
                        
  .navbar {
    text-align: center;
    margin-top: 34px;
}

.navbar>ul {
    list-style: none;
    padding: 0;
    display: flex;
    justify-content: center;
}

.navbar>ul li+li {
    margin-left: 114px;
}

.navbar>ul li a {
    text-transform: uppercase;
    color: #fff;
    font-weight: 600;
    letter-spacing: 1px;
}

.shop__menu {
    display: none;
}

.sub__menu {
    padding: 30px 30px;
    list-style: none;
    background-color: #fff;
    width: 100%;
    position: absolute;
    left: 0;
    top: 108px;
    display: flex;
}

.sub__menu>li {
    margin: 0;
    padding: 0;
    text-align: left;
}

.sub__menu>li+li {
    margin-left: 50px;
}

.sub__menu>li ul {
    padding: 0;
    margin: 0;
    list-style: none;
}

.sub__menu>li>ul li {
    padding: 0 !important;
    margin: 0 0 10px 0 !important;
}

.sub__menu li ul li a {
    color: #080808;
    letter-spacing: 0 !important;
}

.navbar ul li:hover .shop__menu {
    display: block;
}



