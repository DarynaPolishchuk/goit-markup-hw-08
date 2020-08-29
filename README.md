/_Секция наши приемущества_/
.advantages {
padding-top: 60px;
padding-bottom: 60px;
}
.advantages-caption {
text-align: center;
line-height: 1.14;
letter-spacing: 0.03em;
text-transform: uppercase;
margin-bottom: 10px;
}
.advantages-text {
text-align: left;
font-family: $main-font;
  font-weight: normal;
  line-height: 1.71;
  letter-spacing: 0.03em;
  color: $subtext-color;
}
@media screen and (max-width: 767px) {
.icon {
background-color: #f5f4fa;
width: 450px;
height: 120px;
margin-bottom: 30px;
padding-left: 190px;
padding-right: 190px;
}
.advantage-list-items:not(:last-child) {
margin-bottom: 30px;
}
}
@media screen and (min-width: 768px) {
.advantage-list {
width: 100%;
}
.advantage-list {
display: flex;
flex-wrap: wrap;
}

.advantages-caption {
text-align: left;
}
.icon {
background-color: #f5f4fa;
width: 354px;
height: 120px;
margin-bottom: 30px;
padding-top: 25px;
padding-bottom: 25px;
padding-left: 142px;
padding-right: 142px;
}
}
@media screen and (max-width: 1199px) {
.advantage-list-items {
max-width: calc((100% - 30px) / 2);

    &:nth-child(odd) {
      margin-right: 30px;
    }
    &:first-child {
      margin-bottom: 30px;
    }
    &:nth-child(2) {
      margin-bottom: 30px;
    }

}
}
@media screen and (min-width: 1200px) {
.advantage-list {
flex-wrap: nowrap;
justify-content: space-between;
}
.advantage-list-items {
max-width: calc((100% - 60px) / 4);
}
.icon {
width: 270px;
height: 120px;
margin-bottom: 30px;
padding-left: 100px;
padding-right: 100px;
}
}

@media screen and (min-width: 1200px) {
.advantages {
padding-top: 94px;
padding-bottom: 94px;
}
.advantage-list {
flex-wrap: nowrap;
justify-content: space-between;
}
.advantage-list-items:not(:last-child) {
margin-right: 30px;
}

.icon {
background-color: #f5f4fa;
width: 270px;
height: 120px;
margin-bottom: 30px;
padding-left: 100px;
padding-right: 100px;
}
}
