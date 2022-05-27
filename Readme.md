# The E-commerce Project Structure

> #### _Each page has 2 Constant Componenets Header and Footer_

> ## Constant Componants

> 1.  ### Header
>     1.  #### Logo
>     1.  #### Navigation
>         -   ##### ProtectedNavLinks
>         -   ##### NavLinks
>         -   ##### AcountLinks
>             -   ##### SignIn
>             -   ##### SignUp
>             -   ##### SignOut
> 1.  ### Footer
>     1.  #### SocialLinks
>     1.  #### CopyRight

```

```

1. ## Home
    1. ### Header
    1. ### Hero
    1. ### Fetured
    1. ### Contact
    1. ### Footer

```

```

1. ## About
    1. ### Header
    1. ### About
    1. ### Footer

```

```

1. ## Products
    1. ### Header
    1. ### ProcuctsVeiw
        1. #### Filters
            1. ##### Search
            1. ##### Order
            1. ##### by Brand
        1. #### ProductCard
            1. ##### ProductInfo
            1. ##### GoToProductPage
            1. ##### AddToCartButton
    1. ### Footer

```

```

1. ## SingleProduct
    1. ### Header
    1. ### Product
        1. #### ProductImagePreview
        1. #### ProductInfo
        1. #### AddToCart
            - ##### CartAmountButtons
            - ##### AddToCartButton
        1. #### ProductReviews
            - ##### SingleProductReviews
            - ##### AddReview
                1. ###### AddReviewInput
                1. ###### AddReviewButton
    1. ### Footer

```

```

1. ## Cart
    1. ### Header
    1. ### CartVeiw
        1. #### CartValues
        1. #### CartItem
            1. ##### CartControles
                - ###### CartAmountButtons
                - ###### RemoveFromCartButton
    1. ### ProcedeToCheckOut
        1. #### TotalItems
        1. #### TotalAmount <sup>cash<sup>
        1. #### ProcedeToCheckOutButton
    1. ### Footer

```

```

1. ## CheckOut
    1. ### Header
    1. ### CheckOut
        1. #### PaymentTypeForm
        1. #### PaymentInfoForm
        1. #### PaymentFinalizePayment
    1. ### Footer

```

```

1. ## Orders
    1. ### Header
    1. ### OrdersVeiw
        1. #### SingleOrder
            1. ##### OrderStatues
            1. ##### CancelOrderButton
    1. ### Footer

```

```

1. ## Admin
    1. ### Header
    1. ### AdminDataPref
    1. ### AdminDashboard
        1. #### Sales
            1. ##### SalesData
                1. ##### MoneyAmount
                1. ##### NetProfit
                1. ##### TotalProfit
                1. ##### ProfitComparsion
        1. #### Products
            1. #### ProductsData
                1. ##### BestSellersProducts
                1. ##### BestSellersBrands
                1. ##### ProductsSold
        1. #### Customers
            1. #### ProductsData
            1. #### CustomersData
                1. ##### SingleCustomerData
        1. #### Edits
            1. #### EditProduct
            1. #### EditBrand
            1. #### EditCoustmer
    1. ### Footer

```

```

1. ## Account
    1. ### Header
    1. ### AccountInfo
        1. #### SingleAccountInfo <sup>A.K.A name||password<sup>
            1. ##### Value
            1. ##### ChangeValueButton
    1. ### Footer

```

```

1. ## SignIn/SignUp
    1. ### Header
    1. ### SignIn/SignUp
        1. #### Form
            1. ##### Input
            1. ##### Button
    1. ### Footer

```

```

```

```

```

```

# The E-commerce Project File Structure

```

```

## SRC

1.  ### Pages "Veiws"

    > #### _each page has 2 main componenets nav and footer_

    -   #### Home
    -   #### About
    -   #### Products
    -   #### SingleProduct
    -   #### Cart
    -   #### CheckOut
    -   #### Orders
    -   #### Login/Rigister
    -   #### Account Info
    -   #### Dashboard

```

```

2.  ## Componenets

    > #### _F->somthing_ //this is a function of the parent listItem
    >
    > #### if _F->somthing_ is not present then the component is a static one

-   #### Navigation
-   #### SocialLinks
-   #### AcountLinks
-   #### NavLinks
-   #### ProtectedNavLinks
-   #### Hero
-   #### Fetured
-   #### Contact
-   #### ProcuctsVeiw
-   #### Filters
-   #### ProductCard
-   #### ProductImagePreview
-   #### AddToCart
-   #### AddToCartButton
-   #### CartAmountButtons
-   #### ProductReviews
-   #### SingleProductReviews
-   #### AddReview
-   #### CartVeiw
-   #### CartItem
-   #### ProcedeToCheckOut
-   #### CheckOut
-   #### OrdersVeiw
-   #### SingleOrder
-   #### AdminDashboard
-   #### Sales
-   #### SalesData
-   #### Products
-   #### Customers
-   #### Edits
-   #### ProductsData
-   #### CustomersData
-   #### AccountInfo
-   #### SingleAccountInfo <sup>A.K.A name||password<sup>

```

```

3.  ## Assets

    -   #### images and stuff :)

```

```

4.  ## Css

    > #### _Other CSS will be within the componenets using styledComponents_

    -   #### index.css

```

```

5.  ## Utilits

> #### _Utilits functions for later use like PriceFormating and Array's data merging etc..._
