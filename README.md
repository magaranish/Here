<html>
<head>
    <title>Photo Gallery</title>
    <style>
        div.gallery {
          margin: 5px;
          border: 1px solid #ccc;
          float: left;
          width: 180px;
        }
        
        div.gallery:hover {
          border: 1px solid #777;
        }
        
        div.gallery img {
          width: 100%;
          height: auto;
        }
        
        div.desc {
          padding: 15px;
          text-align: center;
        }
        </style>
</head>
<body>
    <h1>LOOK</h1>
<div>
        <p id="content">A photo gallery</p>
</div>
<div class="gallery">
        <a target="_blank" href="https://www.iciclesadventuretreks.com/uploads/2019/07/view-of-pokhara.jpg">
    <img src = "https://www.iciclesadventuretreks.com/uploads/2019/07/view-of-pokhara.jpg" alt="Pokhara city"width="200" height="300" >
    <div class="desc">pokhara city</div></a>
</div>
<div class="gallery">
      <img src="data:image/jpeg;base64,/9j/4AAQSkZJRgABAQAAAQABAAD/2wCEAAoHCBUVFRgVFRUZGBgYGBkYGRwaGhgZGBwaGhgaGhgcGBwcIS4lHB4rIRkaJjgmKy8xNTU1HCQ7QDszPy40NTEBDAwMEA8QHxISHzQrISs0NDQ0NDY0NDQ0NDQ0NDQ0NDQ0NDQ0NDQ0NDQ0NDQ0MTQ0NDQ0NDQ0NDQ0NDQ0NDE0NP/AABEIAKIBNwMBIgACEQEDEQH/xAAbAAABBQEBAAAAAAAAAAAAAAACAAEDBAUGB//EAEAQAAIBAwIDBQUGBQIGAgMAAAECEQADIRIxBEFRBSJhcYETMpGhsQZCUsHR4RRikqLwcvEVI4KywtJjkxYkM//EABoBAAMBAQEBAAAAAAAAAAAAAAABAgMEBQb/xAAnEQACAgEEAgICAgMAAAAAAAAAAQIREgMhMUETUQRhFCJxgQUVQv/aAAwDAQACEQMRAD8AyYpRRRTgV9AjzwYpwKKKeKYgQKcCiApwKpADFFFPFKKAGinininimAMU8UUUooAGniiilFMQMU8UUUooAGKUUUU8UABFKKOKUUDBpoo4pRQICKUUcU8UABFNFHFKKAAilFHFKKQyOKUUcU0UABFKKOKaKQARSijIpooAGKaKOKaKQARTRRxSIpDIyKVHFKgAIpwKKKeKSAaKcClFPFMQ0U8U4FPFMAYpwKKKeKABinAogKeKYAgU8UUUooEDFPFEBSimAMU8UUUooAGKeKeKeKABilFFFKKABilFTXLDKFLKQGGpZ5jqKCKE0+AoCKUUcUooACKUUcU0UADFKKKKUUhgRSiiimigAYpRRRSiiwAimIo6aKVgBFNFHFKKVgRkU0VJFCRQxgxSoiKegAIpRTxTxUpgNFOBTxTgU7AaKeKcCiiixAxRRTxSAosBRSinAp4p2A0UooopRQAwFPFPFPTsAQKeKKKUUWIGKeKKKUU7AGKksIpmTGwHSZ8fAGpOzbIuOysyqgEO7fdLGFjxn5A1H2mjWiVbd2LYmDmQ6nmDOI8a556tvFcm0YbWyzcdldLTzoIUkAz7wgMo6iZ8ZIqtxHDsjFG3HwI5EeBGap+2ZWDky0gic7bf7VqWuON8LbdVV1kI8wI3VGmcbgGcSBURk4P67HJJ/wAlSKaKk000V02YgRSijimiiwAilFHFNFDYA0xFFFKKLACKUUcU0UrACKaKkilposCOKYipCtCRRYwCKaKOKUUWBGRSoiKVKxhiyaRt10Y4BGB0iCpM74E4J8I+hqrd7PY7Cd9s7b7VzR1kzeWi0Zlq2OdK5a6VY9iRUbmrUiHHYqaaILUrLSC1eRnRHppoqUim000xNAU9PFPVWKhqVPFOB/nL1Ow9aMkh0xqVRcVc0HSCCYyQQQPCRgn/ADrVnsdFuOgcNoTLkH3mnAMbAgEehzms5aiirKjBt0BFPFbnG3LJuE3U0HUSO8FDgsZVs4jqD4Gj7N47hjcKexVkbYkSy42gzqH+eFZ/k7XTL8Dvkwoo04Z291TnnGB1Pjy9SK7fg+NKlUde8BGoxpZJMEZwwA5xzG9S8XwqkarJWJJYYCnAEryn9+kVk/mPijRaC7ZxXaXZyohKkQpAEtJYlRkQInJPxqpxF/VatKTJQOORhZBAnfHTxrX7S4cIjAhmlBq0jVpLZk9AHBz4kefKqCW+v+9VB5bhL9RFiSSMUCmfIVK6E7YA60IUHBwK1Mx+HvkMImJyPDw8a2LtggmJInBjBzyqpwACtrCIwUEw5hZjmSRPlzrqLHCWLnDaQ6oyrrMsIVm1SoJMgAyIn5mal6zg/oa01JHOxSin4pXXDkFi4mfeG+mP5TIgjFHY0ujOTBWTyjT6mfhNWtZEvTfRFFKKSupEzjy8Ns0Vgq+xzG3OrziRiwIpoqc2qjZaeQsSOKUUnYASaJ71vSAgJYEHUcegXpNTKVFRjZs8B2GHts2qWUwVHLp51Fc4NhuseFQNeFlUdCQ+rv5MGBPlEGPWrPaXFsHGkgq41oc5DcvP9q5fJOzoUIpFR+z7n4Hzt3TVVrTdDV+3204lWMxEEciB/nwrSftdVdS9vUpyDpnUOhnar8slyheOL4ZzBWmIrtuK4bhnIGgKWQOumQGVsiIxONqzuO7MslQbDajAxIMk7AUL5CfInovo5gimqW8hBIIIIMEHcEdaVbWZUdhwyOxLMQSoTOlV1K/tAyvpwZiJgb1Lx3Zw7r2tQJnB6wII+lZNntxFuEA9woFYnusrKzERJgiG2rS4ftG040C4gEEyIiAdwT4meXPpXkRyR6WzKrWda+5LL7ykgMDMGOq+nOqHC2FJlxAJIOQSvpE8jXTJxlog99NUMWhl94DvRnnBx4jwqu9oFTKgkqJOPeh233zr38K1jqNKjNwT3KXAdk2bjOJYsoDKNlKnAI9ah4nsdEyzOIgkd3AkhiDzgjNB2XxTW7mpZYKkQTB0klhOMbHeuk4i8ro7pBBR3BPkQRHmDP8ApFN6sk+RYRa4OZXsu0zoiXJDGJ59Nq0b/wBldMFGDDYyCIOB+dY/E3hZ4gugDoWBUTgrIbunwIietao7fvODGgSQdIiYwCWLeonFVLUkqpkKEb4Ih9l3YSGUbxgwSCRv6VznFdxyjCHU6Su5n6Vtds3eJZVUH3UOuLihASN4nwaJ61jWjeLl1VUkLkBfujrzOM9a0hqy7aM5wV7Ir8XeTQQry0jAVhHXJjyxVG9eXAQuBGQWnvH3ojlgb0fFIQxJgkkmRGTOYip1SyqHWsmVOpWII2lRIjOTPlEc9XP+yVH0Dw6M6R7PuLu+xjfeYmAa6HhkSxKshhwQSVcKSJMFoweUg7QedYN7iSwVLLXApGnQQpMAkgArlt25Tk1KhbTklnPvOzE6REALn3omT8OdZT3W/BUWkavH2rd4jQdDqoGgmNWA0gsAAYIzzioezbnsgwZcGckEjAHMHYETsRtisu/2iPaQ76j1IAmFA0iegj0qinaRaVV5gjAUjSCTucyf88uPU+WorFKzRRbdnS3O13Q9xyfyB6gnP7UQ+0rye/J6xEZ5RIMx5Y51xpvi7qAvLqXMFQWQCAwhveyQPI1TftFNJ7zs5ELpXSdR+7t7xJUwTG29cD1NWUjSkd432kVnl1ViRkgafAjUIJ60P8Ml2Tb7s7KWGfKYOJHxrh7V8AAlXE4Cu+ojEmDknaep8q0bfFuQNDORgEE5G3WDMEHPXFaR+Tq6ct3aE4qRrPwrAkHlg+lHwvC6m91mAOdIJYwCcAZ5Guefi3mZckkgjO+/kYxn/arPBdvXUQtCjaC+6mO6ZJwdq7Y/Ptboz8W503ZiLra06tuxZ0ciAogDQcMJ/Kqz9ng6yj4UaiWEHLFQDEiSfrXMcR9pyXJ9oEdpJYOoGdxAOkEmDkfKoV7TvgZvNoYggEZz1YjnB38aPy0ndMbhseqJwSuiLcCAaDpMzpP3SpJBK7GOWZ3xhcTwKIGVHU+KuJ04JBE59351zdntS9eVUZzokS3eDBV04CnG0ZjbwpuJS2NIlvukwcvOQBG/0gjJrB/MSexo4Wi5dtSRuR/n71NwdwIzarQeY+8UKkZBBG/kRVVOIVAQARu2WjaJnltBieRneKX8aAYDCTyywM7RmtP9hBqmmZ+JrdHRNcR0Dxpc7oJjciVYgD7pMSfOql+2RsrHGrYbfHbas8dpBe60DVgSMTygY3qe32uygQJAJjYBT197qOeM1cf8hFCelZCp1uFncgeAnatn+FD2nRoFy0SUOBqUL30nqILAeJ8ayhxVtpYqF3Y6TMc5gDAxyq7w7q7SN9QYiTz3/PNW/lwm1THGGPJDxEOBI7x3I2OWg/0lfhR2uKbR7PB0SyTuAfejx6eVHxFspKgBhmCTswA2I3wwPqKzXQqxkEdd8TsfnW8aaJezBSZx411Fp9XDzuAFiY94SrrPLAVvWsfhb9pm0+7loJGILHTtkbjEdfKta3wyG0yB4LENoJEzsrDqrTp8DG9TOSsqEQLnEqUKOsBAjowjUoZBqgHcFhJA/F6VofZu4LSQykq8sGIUqDyQzscTv+tY3GodDtvChDyjRC6/HvLHqDVe3xg9xdQQhSpPKAwePGSfhUtZKik6e5sdsdnC6BftspBHfBJkGQI6mCQPhSrEtdrXLTuUaJMY90+MeO9KqWa2IeD3MTi3Osq3XbO/kagCNPdBPOBn1rt+IvSVYINSggYG5xPoKFCJLMxJYQxjbvBho/CJGetRGeMaoGlJ8nL/AMFxHu+zuyDMaGkHrtNWzxvFooRmdQRswkxtzGrY11C9qsp1FQ5grO2PEx49KyOJ4u6xLsBJxAHgYkzjMHHQUKbfKRVJcMBuLbRKPqe42tlzGnEajgEy0mBGOQ3t2u0bVu2Q662JOsmO9mCukbDAgcseNc2/EOgZGYlmUQNQkAbAEnAgnwFUny0sCe8GB1EiR4D5DO2RXHr/ACFG4x59lR33NG52jrIAVlCjGGgCASJA3gTmPpUC8YDhG2xPd5EyZJkwZ8D1jNYvEOAwY3H0AAlX1d4asMrAEggD1AG1Dw/HIzqhcojBpbQixg6NJDGWGJiT8M8jUpfs2y0aZ7ZBYqSGOzEZWRg4zPTr8KZe0TKHQhAmDqY6cgxtgkcv8DP2WnDq6gC4qwyuwVTouQE1mDqOolfGMDIFUeHKBBAOlRqcaiFAGWB6qJPPc8hRa/5sKZ09niNbHUVBz+KM+Md3FVLzd/SNpmAcTmIXc7GudTj0UrF1hE5DKVkzOpjAY7Hn4Ec7C8SpZYtq5WIDs1s8iMoR+IR3YhpiDNbR1dSO1icYmnb7RX8UDKyAQATy1Tn0nb4znhbj23cQRy0sNYA1GYIxhQYM7iMwKl4XtPitOvh+EtqcT/ywjaBJJNx1XYg4nkOZipeA+0HFHWz6dR5wmncBQkHIyTPXOZznqzm1vIIxiuUcuVUkzcIYDPuyVzE92SPDnGYjNXhODUNctujsgIY6QwAlyhLKD3hIx5Eiul47t17hGvcH8KNG+TjAgxnlUScXpUrA0ndRpIPhB2idtpzUw1K5TBoz+D4G0o0quomDjUQVjAG5M5JoTwFpcp3ZOcKwEmMyupW3HTI5irnD8CHJYPGrLxlpnEGdIMT/AErjFRdp9kuO8HLMuvTJ77Yy0kxOJCzzzsFFRjJ/snsDZjWrt9mZUuBkBILEKpkEAqsSCfHnMmt7hkcTOrDRkbETGkLssHl85gUbVvAkkAidCwGyoEOcjkfHIyM1btFQpIVnRkdSe9mSNLLpIlgARqHhNTqPLYOCS7wFq+ECuquDlkA1hYkiC0iDG8nliua7Usi23s1VtIZoKljM4g6RGoFCCJMaY5Y07XHi0fZw4ILiWJe4zzqnSO7BneZxmIBGgly6zKEUMGVWdy5QKZIAzIJjlM9YxVRyh9oG0zDs8CGlVQMFUMwxIdydOrUO7AAwTmOe5vdicLfGpGS42ka7algQAhBgGYEyBAO843racBRFxw3OW0IQG7sSf8OKz7/a6Wj3FLtBnSVTSMruDkyBgZzmDiktWUpVVoGh+1LV5UU+ycowle8XLaVwHExbhthB2iN6DtG0urWFdX9lbGuGZSptKYZQZ67Dkaq3uNve1Lo720GjUzOzoNaK2lkQYHeGRiVOc4sX7zhlZXTQLdoau8EJGtQE7uSdOJOByNU4NK0qGuGQpdEBSWfWvdOyk8oEmJMc4PwAK3wpuDXfTRo7wglSRvnvQM467DFXLd7QC7wQM6tQbTieQPxx8sue0Q3eS2z9IV8gzuYEnA7pwSfWsW5dIEvZGzsACUcrjurGBjunO2dts+tV+H4aCXDOpWTLloInoSZ225Rz5273GFHV2ZVDghg6IrwIiNRGqMbE7jFRXbyOolfbRksrpp1QZJUNsfX5ULJBsTo4dRpVGJO+sd3ImFcAc2wcjVWtwpeQSeY89snBgjAxA3z1rjOP4Bj3LduLbEFmguULbZUAgQD3TI8e8K1+B4JkQXA52AgkquT70cxC+E+tEoqKUkwW50d4u20j0HhzG2wx4VQfhHPKAKh4fijhgxEZyzac+JMH6Vq8Bx0MA8EN0Mmu7S+aklGXJlLSfRX7PshXHtE1IRpIBIIB+8I3I6c63eJ4FkQeyualHeAnMAyIETz+tWUCHYCpHUAbbV0S1LdjjsjMW7bIjQ6EsC0aWUjmsfhyfjzqhxvDkKFQyupm6RIGDPr8K34BEgb+FRm3n3RHifyinGdA90cqbTqTI+h+lKulPCL/AIKVX5iMRtdEXJ/yKK4nPf60PsW3AMeX1qU0Q0xgacNHOiFg+NO1kASSflRkgxZS47hEuQzrJUGMlQZEQYiuO42yyu7akVBOrWrACOqiNQyc7eNd045R13OflWJx/wBnhdTRqaZlmIJkZMRMT4iK5tbTcn+v9mkHXJyw7QtBpVmdzHuatMTAABMTnfJyR4V0HAG+6SMagFAKNiDqWcyWI3nGI5VBxfB2Oz0V3tly7qgUASTDNqjaf2ii/wDyltTf/rmLcMQ1yGIIBYQqsD3STEnlWXijFW3uaKUr2R0A4DiF4fXxDWr9l5Vz31dUXUe8oBJgryIjJrGTsJWZ7K2yCe6we5DlQRcSBMGZEkZGZ2oG7elfapb0lHcpb1HvahpZXVWDMsSII2LGMmsbsvt2/cFx0XWw1MyFi0KF0qQDqYqFaI2lQYnNYuHcS032a7fYR7cPbtWbk5a091tZA1YQaeZIkGQYGOdWP4q/Yt67XCog0kvoNlT3QdXeVJYwBHiY87XY32q4gOtxbNvQ5ZmLagyM1sGIJEAspg+O3M6Nz7Q3L4ZzYCKrPIKwSzKshswCdB3369LjNJVLdiwlyjmuJ426oR7iPZ1qukGS51SQe792AD6HaDGFd4l7MhrbMk6hpClQv34IJ0gchn05dT2h2xZMtfZExbVCFY4thgseEk7jEjauW4v7Wh9VpEUW3Hs2LCDoIhjpX3TPMTgdazjBuWy2HLbszO0O2TcC91kgR3WyVwWJ9AMRHnVjh+xLn8GOJAb3ho72NJuKuAJgluRjmayrHD3Xb2tm20gz3AWg74AEDfFdXd7L4t7bWV4i2toKj+zLrMvFxxJEjvsSJMT0ro/SCrglJsodm9oXmgs7Ke9pJVCCunIJiB905/3Hie17jkaWwC/I7d0d0Ewzd4SM746VtcN9lri2CEvprNxiYVbiG2yDOULatQ07wQYoOyPsfD2ybuVZjrRV2IGgsCcqCp8CGHjUXBvlUPGXo5xeB4hkZjaYlGJ92YkPIHMAFcqBjExUXaNy7bv+yt3NaroCNbiGBQaSCBnBjPTOc16Bw/B8bp9m1+xDKyvNkOZedR7xEElt1jlUD/ZBla06OCyJNzWqsHca1UhTIUaSORg53zTzj9CwZz/ZrX277MUYhTqBDFiF0gulyVciSNPdwcE1GeP4jV7NmQRAYhWCsSGJY6UlQeeBspx3jWoOyeKDFfZPGRM2JJwRs5USpiCB7u+TGnwfY/EHSLlvQch8qwYZ6DAPQT4nas5aklzTQ8Tl+2LnEQxa/YVAQNKFoBCkwDoiTDHrPwqrxX2avovt9dvYsdLMzEBssAFnTBBPh8K9EufZ60GDhP8AmaArsCBJGrMd7MaDj9qv8NwYYC3cRXtjXCu9sidLaTgAwWj452prWS4Q1C1uzhr/AAxt27TXv+Wz6VZsyCbUKDpYaoIcgE4nnMGjxXZxuLbs2lZpsqUJRpYpcvyZwFGiWgiYiM4PoD9mWzpV+Gt3IDBS3syFnIAJQjA0rv8Ad6iK3ey7BWxC29BWVVAUKFYUAFkQgABuQ61Xm24KcVueODsfjEDPYXWLZIJALNgyGCuIaeUCYiql7i+OCgBW0thWVQynM911BnIJBnbwAj3DgeGZmAuWQqxClSrgEh+8IURlvXWfGol7NCTot6QmpQdKjDGWIgYB3P50PUi96IxZ4jc7P4u4us2brJaBLGSwVZbVqOSskGJ3jnS7HDLqZVXQdR77HlA0kLz+G3lPt79mp7H2Psreh9WsaAJGuUEgARG9Ubf2V4fXaU2ECWmchVLjLJGrSsAt7hk7UnqpqqDFnm/ZfEHiGcICFtqdILArqM+yEmMsyiQWG5z0t3gQ2i7pDKUQsqHSrzhWI06AxJjG3ms96exCENrSUR9Swikka1CO2pxqDESNW4DEDTJoO2uxb3skWwiMUXSVYlNY1EgSB+HSDJnuj1i4VxRXByVngLhAfCj8JZAIkCSJ3OctOM7VftdkK4g5B3A04ErGQPGeo+nR/Z5OItPLIBKOcqdesguQRnSuoQI3nyqfiHRFuXvYurOwe4FUrJAUEwF3heYyT1NCUdgdsrrZ0xpxGPSnKzvWzZ4O04DqTDAMORggETOxg7edG3ZaePxFdK1YkYmIIFLUP9qvjsZtTEtIOnSNO0atU5zMjmdj1gA/Z1zMKDG0GCRGN9qfkQYsqT5U9PZt3SJNplMkENDDwMrI2+dKnkgpopNfcfe+n6Uv4hvxfIfpVZnpprqpejmbfstC+/4vp+lM7k5JquGpaqKFbJHduR+ZqM373409dZ/Ok7xz+NYHH9oEKwBzJjP7VE5KPI4pvgX2rd2tprKsBdUwJ3CuM6yQRk8qo2L7KVnQdOv3kBYE5LFwwJPScCKj/wCIFxpcGJnBzuf1rTQ2jz58wNuc1zaijNWmbRk47GJ/DozhvZAsrkEkzJOkLuTgYoL17XfDMio1tANSFkOEgayG7zZidj4jFdovDWj3wwj+IU7CYlZmOVYFvhbS33z3WCE9MoS4HgDFczlj2bKVh9mMbkEfeIAgbYJEdIANXeFsXFLEXCsEgqQrK0rvG4233ra+zgsK6trGkMv3iRIQiDB8dqufaLjEIOkzLiMmI0Ebx4VEIqSsp6jR5t212azsGm40AR3+6isRhdQJjPXzmubtllbT3hyyQdzzgfnXpXF8SuhYEk2UHOAQ4kfXauc4xUJche9oaMkd7Q2n5xWsdWnizOS7L/2c+0NxbKot22gUxAtFj5li4knrXQWu1Lo34hT3Q0+zWTIBk97xryNuHuBvd5/ymuk4XiCeHuEzrCsBgRAQBM+lOWkpO0ylqUjv+H4m5pLniTiFnQkZW42wMT3flTJx1x3Vf4kySFnQoJmRnMHea4bsri7ns3UkibikY5aLg5edQWL91HVi+1wNEnaBymsvF1ZWZ6Ta7QuMQPbkz/8AGsfWiucW8KfbN3lJ91QdyMfCuJ7O7UAJ1SY1Ab9RE55Zqhf7QugcPDYVAG2zL6m9Mn5UsEGXZ2LdpNr/AP7vzBxC5E7bVZPaBLKPaEwSvuoRIIzIGTjeuKXtDVpARVIAJZdctgDvBmInE4AqV+IZWU6idzv0IrNxknwGZ3zcS4E+0bvSdl6kYxjans3Xcge0bPTSPHp4Vx3F9ouESCcKeXV2O/8A1UfC9ssAgmDqzJIG0b1WI1I6sO2B7RyD/p89yKu8NZL2yxuN3cDK/wAvh/Ma4n/ibaEyZxPlz3rS7M7a02zOxJ6Dmv6U8dh2dDwXDy6g3GO+5XpPTwo7iQzD2r4JAyn/AKVzHDdunWsDEnduu24HXrVVu2nLE6h7x2aQfKikkTkzsrvChrer2lzcyQwB7pXkFgb7xVTh+EXWo9o51Npy68x/orG4Ptlv4e4uSSH5gQSEjMZrD4TtZ9aSSSLgOOnjy+dF1wDUXydtp3/5tzB/EnSfwVU7asoEDF7hnUI1iYnl3R18K5632sy6pOCwwYA90jlvQ8ZxZe2kGYLc/LG1UptqmyMIp3R1XYCC46IXcqQwI19FkVa4/hdLOodiygYLMRkfOue+znGsjodoZuvNYrQ7Q41jcc4yF8sDkKuKtILSexv2VUKBqbYfeI5U7afxv/W1YycSSBnkKka/it1pslysu+0GojW3L77eNRvd/nb+tv1qj7SgN3/P8NWoMm0WBcP4m36mlVT2lKqxFaG0UQWqftn5oP6ifotO1w81X4N/6114nHkWvSlA/wAB/Sqg2wifD9qcF+ijyn9KMQyJ7tsHl84rN4ns5TsonzVv+5auG43PT/dUdy+ByA8SD9cVEtHIpalGa/ZOR3kHmEn5LFSL2ZGSxaOQUAftV5L4/Gvz/wDaiDqfvD+386yfx0aLWHWyAukGBIOSQJ8IrPfgSXkOPiT8ZWPnWrqgSNvD9hULcQJM930afoPrU/jxY3qsDheCAOrVkHr+hxUnE8IrSWmZBxJ6xyp7VxTtPnDVIz+f5/ODVLQXoXkfsqnhFIHcYwIzq2metVX7OEk6I5fe/M1oO42M/UfnQC4QdxHip+tS9CPoPK/Zz/E/Z4Ple7B+9gH1maO12OgUgqDOMOTPyNbftG397ykfv86jdNU92D4s3601opcIXlfswbfZYyEYiTIlg23hvzo27Gk5ViN5kAH03rbRCBhh/eT83qLQ27EHpKgGktBLoflfszk7E05VQOsn98UCdlqQBq25DQfnNawRT7x57AHHnAqVUHJiPX9ab0I+heV+zEfs5RvpE+Bn10qR86NezrbEYdo6Bo9M/lW4WjGqf7vnUFxEfr5gAfMiKPAg8jKb9lodh8hPzUVVTsjPPBmGRwPQqa2LQxGn4x+VPctv919HnLD4E1T0I80Jar9ma/BQBCAx0UH5lKc8LMSh55MD4fCtG0rfefV4xHwxUjLP3iAOhpeBSK8zRlWOy4OogDP4jmpl7PTYwfJTHxCir3swOc+cfrTsxOPoPpQtCMeheWTKy8DbAgIY8Fb8wZqo/Zy/dtk5xOPyFaaYMFv7mB+s0JZdon1JH9wpPRi+h+Rrszl4UDezM9TPyLmrFnh8R7JVHnj5Grgt9D9fyNJGQbsPKQD8zTWgheUKxa0/dA8v3qZ7earq4nA/uU/SrTGatQXoM/sICmLeHw/egDjp8v2p58PlTwDMQb/CaYik0VHqHhTxE5haf8ilQ6hy+k0qMQyMpNHOw39KN/5mmfhkmQijzCfQVnf8VdsBVn+W9IH9pp1uXGaSkRzD6v8AtUV007MKLVwjVCMF8Fa2v5TVm0jDLM3/ANgquA7DdvUXPrpNSraI+8J8nb6kfSgRbdB4/wBR/Okvd2/In6GqV2467uv/ANdz8mNGhdhJIPjlfrSoexeLrvIPnANQ3byjb5tI9QTVckbHbqGYfTFOpRd2PrccfLUaWIWSo6ESIX/SVj1xUV3i9Jw6keZj10/pQuqN98T/AK/3p0tYx3uuZ/WlSsLZYs8WCJBHoHPzIojxEnO3Vl+hx9KgFhPFT/qg/lTk6di5P+qR8zRSHZIeLtjAyegmahHGrPuv623I+Og044wj7j/2/nUyXCfuuvnH5UVQbMiPFhsR6aHH1QU5Z+Qjz1Gjc+PzP/tVZ7iA+6JG+P0ajYRZIJElSCPCZ/pNMbuI0MT/ACo4+ZFUbvFjE3UTp3D+poEuPyfUB0Qx6QIp4phZavRGVdB4hfq0mkuPxn0/NTUIuORARD5kfQLNJC2RoX01fQjPpRVcCLj8S3JHn/SI+bVEvGPsVYf9M/nQq5O5x+FZB+maMXQDADDzAB+bflRSC2Gi6t2YejJ9TR6ORJ9GZp9JpizEY2/6fmVk1ELfRh6QfrRQWWNAHeM+rfWaB4J3/pJ/JhTJcIMavlH0EUnczmY8Cf2FTQ7RJ7IDk39bfTVUOlZ94T0lyfm+PhSa4Y3+MR6gmnS9jJX0EfMVSXsVkX8SpMQ59Hj4ipxdTkzD/UW/8jQLdY8y3+ddNIu34APHWPnilT6HaJO8DuD6ID9TVhGNUfascakH/VPyokuqDkpn+YfQ1DjRSkXA78oP/VH/AIUx4h/wjH88/UVF/EqfdZf6/wBjTfxB5iPIOx/7apJ+gtEg4l+aqPN1/Wn9od5X4k/SoTdPJR6o5/IUHtn6J/S6/VTVJL0K37LYuHmB6fvRFp5/IGqntj/L6CfpFL+IO2hvg1LFhkuy0oPn5x+tKqyueaEeYIH/AG0qnFlWiHh6G/SpVqR0YHE321e83xNWUvNo94/E+NKlVInsh4q63d7x+J6VatDenpUDZEu48qu296VKhi6LQY9f8ipgo6cvzpUqyfA48iCiTim9ks+6PgKelTiDAsqNO1RtZX8I36ClSoQE3XyqPgmJmTPnmnpUAyS+PzrLv3WDQCQPAkc6VKkOJb1Hryqi95oHeO3U0qVPoEaw5HnT/e9DSpVD5GVuKxtisTiOIfPebbqetKlVguAv4h9I77fE1Ol5vxH4mmpVaJZO11o94/E1HYvNPvH4npSpU0QO/EPqHebfqa0FNKlUyKRXv1Pw23pSpU+g7LibVXilSpFLgcb+lTE01Kp7DoiVz1PKp0Y9aelUspEtumpUqktH/9k=" width="200" height="300">
        <div class="desc">One of the beautiful scene of pokhara</div>    
</div>
<div class="gallery">
    <a target="_blank" href="https://i0.wp.com/www.tipsnepal.com/wp-content/uploads/2020/08/39358990490_c09709e8a5_c-1.jpg?resize=768%2C433&quality=100&strip=all&ssl=1">
            <img src="https://i0.wp.com/www.tipsnepal.com/wp-content/uploads/2020/08/39358990490_c09709e8a5_c-1.jpg?resize=768%2C433&quality=100&strip=all&ssl=1" alt= "Ruby valley of Dhading" width="200" height="200" >
            <div class="desc">Ruby Valley is well-known its famous for gemstone mining, rubies which makes this the Best Places to Visit in Dhading.</div>    
 </a>
</div>
    <div class="gallery">
<a target="_blank" href="https://www.lrbtravelteam.com/wp-content/uploads/2020/12/pokhara..png">
    <img src = "https://www.lrbtravelteam.com/wp-content/uploads/2020/12/pokhara..png" alt="Boats"width="200" height="300" >
    <div class="desc">guess yourself</div> </a>   
</div>
<div class="gallery">
        <a target="_blank" href="https://i.pinimg.com/originals/92/23/96/92239685b0e31b69daeae2d360602e46.jpg">
<img src = "https://i.pinimg.com/originals/92/23/96/92239685b0e31b69daeae2d360602e46.jpg" alt=" scene "width="200" height="300" >
<div class="desc">guess yourself</div></a>    
</div>
<div class="gallery">
 <a target="_blank" href="https://www.eadarsha.com/eng/wp-content/uploads/sites/2/2021/10/Gandaki-Uni.jpg">
    <img src = "https://www.eadarsha.com/eng/wp-content/uploads/sites/2/2021/10/Gandaki-Uni.jpg"alt="GU BIT" width="200" height="300" >
    <div class="desc">guess yourself</div></a>    
    </div>
<div class="gallery">
    <a target="_blank" href="https://static0.gamerantimages.com/wordpress/wp-content/uploads/2022/04/solo-leveling-2.jpg">
        <img src = "https://static0.gamerantimages.com/wordpress/wp-content/uploads/2022/04/solo-leveling-2.jpg" alt="pic" width="200" height="300" >
        <div class="desc">Animated picture</div>
      </a> 
     </div> 
        <div class="gallery">
    <a target="_blank" href="https://cdn.europosters.eu/image/1300/julisteet/one-piece-ace-sabo-luffy-i102249.jpg">
        <img src = "https://cdn.europosters.eu/image/1300/julisteet/one-piece-ace-sabo-luffy-i102249.jpg" alt= "pic" width="200" height="300" >
        <div class="desc">Animated picture</div>
       </a>
    </div>
       <div class="gallery">
     <a target="_blank" href="https://pbs.twimg.com/media/FMrcJ7nX0AID2UV.jpg:large">
        <div> <img src = "https://pbs.twimg.com/media/FMrcJ7nX0AID2UV.jpg:large" alt="pic" width="200" height="300" ></div>
       <div class="desc">Animated picture</div>
     </a>   
    </div>
</body>
</html>
